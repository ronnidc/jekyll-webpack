# Jekkyll and Webpack

Testing a setup with Jekyll and Webpack

Based on [Jekpack](https://github.com/yfxie/jekpack) by [Yi Feng Xie](https://github.com/yfxie)


## setup

```bash
git clone https://github.com/ronnidc/jekyll-webpack

npm install -g @bincode/jekpack

cd jekyll-webpack

npm run bundle

npm run dev
```

## Issues

1. serve pages from the subdirectory `/src/_pages`
	
		eg. /src/_pages/about.html --> ://localhost:8080/about/
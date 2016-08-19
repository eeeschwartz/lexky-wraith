# [Wraith](https://github.com/BBC-News/wraith) config for visual regression testing of www.lexingtonky.gov

## Installation

```
brew install phantomjs
gem install bundler
bundle install
```

## Comparing two sites

Edit configs/capture.yml to set domains `old` and `new`

`wraith capture configs/capture.yaml`

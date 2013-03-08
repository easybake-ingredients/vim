Drop .chef/plugins/knife/source_ingredient_vim.rb
into your .chef/plugins/knife directory and run:

```
knife source ingredient vim
```

:file_cache_path and :data_bag_path must writable and might need to be set in your knife.rb

The latest available versions of vim for osx and windows will be downloaded into
your file_cache_path and your data bag path will get a vim directory
created which will be populated with data bag items for each version
of vim that is available.


ruby号称语法更接近自然语言，语法糖很多，有些相近的语法只是同义词转换，有些又有细微的差别，记录在这。

# ruby
catch&throw 和 begin&rescue 的区别 https://stackoverflow.com/questions/13484004/ruby-catch-throw-and-efficiency

# each_with_object
https://womanonrails.com/each-with-object
除了 each, map(collect), filter(select, find_all), reject, inject(reduce), 还有 detect(find),drop_while, each_with_index
还有这个  each_with_object， 挺有意思




# rails
时区的配置：https://ruby-china.org/topics/16187

## model:
 1.[find_or_create](https://api.rubyonrails.org/classes/ActiveRecord/Relation.html#method-i-find_or_create_by)_by & first_or_create
 如果记录存在则获取，如果不存在则创建，例如：
 ```ruby
 User.create_with(last_name: 'Johansson').find_or_create_by(first_name: 'Scarlett')
 User.where(first_name: 'Scarlett').first_or_create(last_name: 'Johansson')
 ```

# 

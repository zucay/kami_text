# KamiText

スペースでレイアウトされたテキストを、
幅狭い端末でも見やすくするためのワードラップメソッドです。

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'kami_text'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install kami-text

## Usage

KamiText::wrap(text, 折り返し文字数)

のようにコールすると、いい感じにワードラップされた配列が返却されます。
詳しくは
http://qiita.com/zucay/items/b6b4704f9279fdcb3c00
をごらんください。

## Contributing

1. Fork it ( https://github.com/[my-github-username]/kami-text/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

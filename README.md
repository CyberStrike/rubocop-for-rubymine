# RuboCop for RubyMine

> This is a simple RubyMine/IDEA plugin that integrates RuboCop as a linter for your Ruby projects.

## Installation

- Download the [.zip](https://github.com/CyberStrike/rubocop-for-rubymine/releases)
- Got to the Plugins-Settings in your IDE (IDEA/RubyMine).
- Click "Install plugins from disk..."
- Select the ZIP
- Restart the IDE
- Wait a few seconds for the IDE to load and give Rubocop some time to inspect the current file.
- Hover your mouse over highlighted issues to see the warning/error message.
- You have to *save* a file to trigger re-validation of your file.

### Troubleshooting

- Make sure that you added a `.rubocop.yml` to the root of your project.
- If you use `bundler` you have to include `rubocop` in your `Gemfile`.

### If it still doesn't work...

- Open an [Issue](https://github.com/CyberStrike/rubocop-for-rubymine/issues/new).
- Provide the information asked for in [CONTRIBUTING](https://github.com/CyberStrike/rubocop-for-rubymine/blob/master/CONTRIBUTING.md).

**Important** I will happily merge pull-requests but can't and won't do free support.

## Screenshot

![screenshot](https://cloud.githubusercontent.com/assets/56807/5009481/9bbee3b4-6a67-11e4-8bf9-2a32c3bc3d5e.png)

## State of Development

I'm not working on this project. This is more of a proof-of-concept and *works for me*(tm).
Feel free to fork it and maybe send a Pull-Request once you added something meaningful.

## License

*RuboCop for RubyMine* is released under the [MIT license](http://www.opensource.org/licenses/MIT).

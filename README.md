# svgMonthGridSelector

This is a jQuery plugin explicitly designed to be used with the SVG output provided by the dates2svg RubyGem ( https://github.com/jkeck/dates2svg )

## Usage

Initialize the plugin with a selector

    $("[data-month-grid]").svgMonthGridSelector();
    
## Options

You can pass various selectors as options to the plugin on initialization.

* begin_date (the selector of the input that holds the start date of the range [Default: '.begin-date'])
* end_date (the selector of the input that holds the end date of the range [Default: '.end-date'])
* hits (the selector of the element that will hold the hit count total of the selected range [Default: '.hits'])


    $("[data-month-grid]").svgMonthGridSelector({begin_date: '.start-input', end_date: '.end-input', hits: '.total-hits'});


## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
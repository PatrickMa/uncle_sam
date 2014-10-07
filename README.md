# UncleSam

UncleSam is a program written in Ruby to make it really simple to calculate US
taxes for [US Form: 1040](http://www.irs.gov/pub/irs-pdf/f1040.pdf).

## Breakdown of tax calculations

1. We accept the input for net income and filing status.
2. We apply the [standard deductions](http://en.wikipedia.org/wiki/Standard_deduction)
which will reduce the taxable income depending on the filing status of the tax payer.

## Installation

Add this line to your application's Gemfile:

    gem 'uncle_sam'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install uncle_sam

## Usage

TODO: Write usage instructions here

## Contributing

1. Fork it ( https://github.com/PatrickMa/uncle_sam/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

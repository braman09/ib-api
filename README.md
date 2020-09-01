# ib-api
Ruby interface to Interactive Brokers' TWS API 

Reimplementation of the basic functions if ib-ruby into a small gem


`ib-api`   offers a modular access to the TWS-Api-Interface of Interactive Brokers.

In its plain vanilla usage, it just exchanges messages with the TWS. The User is responsible for any further data processing.

Additional services can be loaded via `require` 

* require 'symbols'  enables the usage of predefined Symbols and Watchlists
* require 'order_prototypes' enables to use predefined orders like: `Limit.order`, `SimpleStop.order` etc
* 


(in progress)




## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/core. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Code of Conduct

Everyone interacting in the Core project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/[USERNAME]/core/blob/master/CODE_OF_CONDUCT.md).

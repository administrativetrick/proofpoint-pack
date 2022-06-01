# Proofpoint
----

This Pack is meant for users of Proofpoint software `Proofpoint TAP` and `Proofpoint TRAP` to `Extract fields`, `Reduce Ingest` and more.


## Requirements Section

Before you begin, ensure that you have met the following requirements:

* A working Proofpoint `TAP` or `TRAP` envioronment.

## Using The Pack

To use this Pack, follow these steps:

1. Create a Rest Collector for Proofpoint TAP if applicable
  * Set an index of 'email'
  * Set a sourcetype of 'email:proofpoint:tap'
2. Create a Rest Collector for Proofpoint TRAP if applicable
  * Set an index of 'email'
  * Set a sourcetype of 'email:proofpoint:tap'


## Release Notes

### Version 0.0.1 - 2021-04-22
Initial release, right now we just drop null value fields and perform some field extractions.

## Contributing to the Pack
Discuss this pack on the Community Slack channel #packs, or fork this repo and submit a merge request after your changes are complete.

## Contact

The authors and contributors to this pack are:

James Curtis james.l.curtis@gmail.com



## License
This Pack uses the following license: [`Apache 2.0`](https://github.com/criblio/appscope/blob/master/LICENSE).

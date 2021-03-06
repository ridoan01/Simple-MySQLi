# Changelog

- [**1.3.2**](https://github.com/WebsiteBeaver/Simple-MySQLi/tree/1.3.2) - January 25, 2018

  - Add affectedRowsInfo and free fetch results

- [**1.3.1**](https://github.com/WebsiteBeaver/Simple-MySQLi/tree/1.3.1) - January 24, 2018

  - Fix `fetchAll()` types `keyPairArr` and `group`

- [**1.3.0**](https://github.com/WebsiteBeaver/Simple-MySQLi/tree/1.3.0) - January 24, 2018

  - All queries now use a global `query()` functions
  - `affectedRows()` and `insertId()` added as separate functions instead of returned in object due to switching to `query()`

- [**1.2.0**](https://github.com/WebsiteBeaver/Simple-MySQLi/tree/1.2.0) - January 18, 2018

  - Select statements now must be chained with `fetch()` for one row at a time and `fetchAll()` for all results

- [**1.1.2**](https://github.com/WebsiteBeaver/Simple-MySQLi/tree/1.1.2) - January 15, 2018

  - Fix return on `delete()`

- [**1.1.1**](https://github.com/WebsiteBeaver/Simple-MySQLi/tree/1.1.1) - January 11, 2018

  - Fix transactions

- [**1.1.0**](https://github.com/WebsiteBeaver/Simple-MySQLi/tree/1.1.0) - January 3, 2018

  - Add new fetch modes for convenience: 'scalar', 'col', 'keyPair', 'keyPairArr', 'group', 'groupCol'

- [**1.0.0**](https://github.com/WebsiteBeaver/Simple-MySQLi/tree/1.0.0) - December 28, 2017

  - Initial Release

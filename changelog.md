> `Changelog:`
> - All significant changes to this project will be documented here.
---

> [1.0.0]
>
> - Initial release.
> - `VACUUM:` Cleans and restructures the database to make it more efficient.
> - `REINDEX:` Recreates an index to improve query performance.
> - `ANALYZE:` Collects database statistics to support query optimization.
> - `PRAGMA synchronous` regulate the level of synchronization to `NORMAL` for the balance of performance and data integrity.
> - `PRAGMA optimize` to optimize performance.
> - Activate `Auto Vacuum` `Full` for automatic storage space management.
> - Enable `WAL` mode for better transaction management.
> - Set the size of the database cache according to the specified value `(default: 2000)`.
---
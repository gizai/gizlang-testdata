# Gizlang test data

The test data of [Gizlang](https://github.com/gizai/gizlang), stored by content. Each file is named by the SHA-256 of
its bytes. `tests/data.lock` in Gizlang names the path, hash, size and source of each file, and `bin/giz` fetches the
objects it does not have before a test runs. The files keep the licenses of their sources (named in the lock).

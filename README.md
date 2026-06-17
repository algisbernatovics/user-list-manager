# User List Manager

A small PHP class exercise for storing user records, filtering invalid entries, and selecting a special user from the list.

## Learning Goal

Practice basic class design, collection handling, string filtering, sorting, and PHPUnit coverage.

## Features

- Accepts a single user string or an array of user strings.
- Filters entries containing blocked marker patterns.
- Sorts the stored list and returns a selected value from the highest-ranked entry.
- Includes PHPUnit tests.

## Complexity

- Time: `O(n log n)` for the final sort.
- Space: `O(n)` for stored users.

## Tech Stack

- PHP
- Composer
- PHPUnit

## Run

```bash
composer install
vendor/bin/phpunit
```

## Project Structure

- `app/Users.php` - user collection logic
- `tests/UserTest.php` - expected behavior tests

## License

MIT License. See [LICENSE](./LICENSE).

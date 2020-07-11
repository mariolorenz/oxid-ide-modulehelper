# OXID 6 ide module helper

Script to generate a .module-helper.php file in the OXID root dir.
The generated file contains all module namespaces and extensions for your IDE to use for reference.
This way, the IDE should find the extended classes for every class that uses OXIDs custom "_parent" logic to extend OXID classes.

## Installation

copy file to `YOURSHOPROOT/source/bin/`

## Usage

`php source/bin/pc-ide-helper.php`

## Changelog

    2020-07-09  1.0.0   release
    2020-07-11  1.1.0   fix getting metadatas, some other stuff

## License

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

## Copyright

ProudCommerce | www.proudcommerce.com

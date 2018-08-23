2018-08-23, Version 0.5.22
==========================

 * fix: grumble grumble grumble (Kevin Delisle)

 * Bugfix: revert breaking change (ellenaua)

 * Bugfix: uncomment accidentally commented code (ellenaua)

 * Revert: moved moment to peerDependencies (ellenaua)

 * Added more node.js versions to .travis.yml (ellenaua)

 * Fix grunt version to 1.0.2 (ellenaua)

 * Updated version to 0.5.18 (ellenaua)

 * prefer nodejs to amd declaration (ellenaua)

 * Move moment to peerDependencies (Yann Pringault)

 * Return error if timezone name is not a string (ellenaua)

 * Return more self-explaining error messages when timezone name is not a string (ellenaua)

 * Ignore latest unpacked data (ellenaua)

 * Ignore .idea files (ellenaua)


2018-05-10, Version 0.5.17
==========================

 * Updated moment-timezone version to 0.5.17 (ellenaua)

 * Updated to IANA 2018e database (ellenaua)

 * Updated data-tests.js job to generate more guess tests (2 for each timezone) (ellenaua)


2018-04-18, Version 0.5.16
==========================

 * Release 0.5.16 (ellenaua)

 * Updated minified files to contain 2018d data (ellenaua)

 * Added group-leaders.json to be used to detect group leaders (ellenaua)


2018-04-15, Version 0.5.15
==========================

 * Updated version to 0.5.15, added release notes (ellenaua)

 * Updated data to IANA TZDB 2018d (ellenaua)


2017-10-30, Version 0.5.14
==========================

 * Release 0.5.14 (Matt Johnson)

 * Update dev dependencies (Matt Johnson)

 * Ensure Intl response is valid (Matt Johnson)

 * 1. Updated data to IANA TZDB 2017c 2. Remove Canada/East-Saskatchewan from test case (ssskip)

 * Convert to tz keeping wall time (Dan)

 * Make all zones available for guessing (Matt Johnson)

 * fix #397  zone.offset has been deprecated in favor of zone.utcOffset (ssskip)

 * Check for timestamp formats when parsing (Joe Krill)


2017-04-04, Version 0.5.13
==========================

 * release 0.5.13 (Matt Johnson)


2017-04-04, Version 0.5.12
==========================

 * Update bower.json (Matt Johnson)

 * release 0.5.12 (Matt Johnson)

 * Build 2012-2022.  (+/- 5 years) (Matt Johnson)

 * Moment-timezone requires moment >= 2.9.0 (Matt Johnson)

 * Add versioned data files (Matt Johnson)

 * 2017b (Matt Johnson)

 * Fix tests (ssskip)

 * Updated data to IANA TZDB 2017b (ssskip)

 * Updated data to IANA TZDB 2017a (ssskip)

 * moving install commands to install phase (Keheliya Gallaba)

 * release 0.5.11 (Maggie Pint)

 * missing TZDB releases (Maggie Pint)

 * Remove Node error logging (Jonah Kirangi)


2016-11-27, Version 0.5.10
==========================

 * Version 0.5.10 (Matt Johnson)

 * Update copyright header (Matt Johnson)

 * update to IANA 2016j data (ssskip)


2016-11-05, Version 0.5.9
=========================

 * version 0.5.9 (Matt Johnson)


2016-11-05, Version 0.5.8
=========================

 * version 0.5.8 (Matt Johnson)

 * update to IANA 2016i data (ssskip)

 * copyright typo (Maggie Pint)

 * update license and contributing for JS foundation (Maggie Pint)


2016-10-22, Version 0.5.7
=========================

 * version 0.5.7 (Matt Johnson)

 * update to IANA 2016h data (ssskip)


2016-10-08, Version 0.5.6
=========================

 * version 0.5.6 (Matt Johnson)

 * update to  IANA 2016g data (ssskip)

 * Pull version from NEWS file for now. (Matt Johnson)

 * add license to bower.json (Ed)


2016-07-24, Version 0.5.5
=========================

 * version 0.5.5 (Matt Johnson)

 * Update to IANA 2016f Timezone Release (Jacob Gillespie)


2016-05-03, Version 0.5.4
=========================

 * Version 0.5.4 (Tim Wood)

 * Handle zones whose abbrs are not all capital letters (Tim Wood)

 * Switch tests to use new default utc format (Tim Wood)

 * Add population data for Tomsk and Kirov (Tim Wood)

 * 2016d (Tim Wood)

 * Use explicit format for test generation (Tim Wood)

 * Checking for undefined Intl.DateTimeFormat().resolvedOptions().timeZone (LeeHoward1)


2016-03-24, Version 0.5.3
=========================

 * Version 0.5.3 (Tim Wood)

 * 2016c (Tim Wood)


2016-03-15, Version 0.5.2
=========================

 * Version 0.5.2 (Tim Wood)

 * 2016b (Tim Wood)

 * Fix dashes in release dates (Tim Wood)

 * Fix typo and copy+pasted line in changelog (Tim Wood)


2016-03-01, Version 0.5.1
=========================

 * Version 0.5.1 (Tim Wood)

 * Use parent instead of global to allow tests to run in a browser. (Tim Wood)

 * Remove isFunction now that we are using a try/catch (Tim Wood)

 * Use a try/catch to avoid potential discrepancies with the Intl api. (Tim Wood)

 * Only return the output from Intl when it matches a known timezone. (Tim Wood)

 * Disable or mock the Intl api in tests. (Tim Wood)

 * Handle uncommon output from Date#toTimeString. (Tim Wood)

 * Ensure timezone abbreviations are in alphabets (Beata Lin)

 * 2016a data (Thomas L. Kjeldsen)

 * Use Intl API for guessing when available (Matt Johnson)

 * Borrow isFunction from moment (Matt Johnson)


2015-12-28, Version 0.5.0
=========================

 * Version 0.5.0 (Tim Wood)

 * Remove jspm deps so that the root package.json deps are used. (Tim Wood)

 * Filter by known offsets before guessing timezone (Tim Wood)

 * Fix issue when an element with ID of `exports` is defined in the browser. (Benjamin Tan)

 * Don't use Math.log10 (Tim Wood)

 * Test spacing (Tim Wood)

 * Add population to filter tests (Tim Wood)

 * Make sure population is carried over to the filtered, linked, packed data (Tim Wood)

 * Don't test guesses for timezones without a population (Tim Wood)

 * Add tests for guessing zones (Tim Wood)

 * Add population to the data set (Tim Wood)

 * Add population counts for most timezones (Tim Wood)

 * Add guesses unique in offset (Tim Wood)

 * Score zones based on the number of matches, rather than an all or nothing approach. (Tim Wood)

 * Create and search through user offsets. (Tim Wood)

 * Use sudo:false to allow faster travis builds. (Tim Wood)

 * Initial work on guessing timezone. (Tim Wood)


2015-10-07, Version 0.4.1
=========================

 * Version 0.4.1 (Tim Wood)

 * 2015g data (Tim Wood)

 * Add 2015e and 2015f data. (Tim Wood)

 * Fix #195: Include builds dir in npm package (Marvin Tam)

 * Specify jspm dependencies for moment (Jon Stevens)

 * bower.json: remove moot `version` field (Kevin Kirsche)


2015-05-30, Version 0.4.0
=========================

 * Version 0.4.0 (Tim Wood)

 * Added composer.json (Hryhorii Hrebiniuk)

 * Log an error if moment timezone was already loaded. #212 (Tim Wood)

 * Fix a recursion issue when getting a zone from an alias when the aliased zone does not exist. (Tim Wood)

 * Fix output of `moment.tz.names()` when aliases or zones are not loaded yet. (Tim Wood)

 * Add passing tests for parsing into zone from the default zone. (Tim Wood)

 * Restructure zone getter to allow for lazy unpacking. (Tim Wood)

 * 2015c and 2015d data updates (Tim Wood)

 * time zone data: 2015b (Vincent Meurisse)

 * add main file mapping for jspm (Eric Chen)

 * Added Gitter badge (The Gitter Badger)


2015-03-16, Version 0.3.1
=========================

 * Version 0.3.1 (Tim Wood)

 * time zone data: 2015a (Samuel Cole)

 * Remove references to tests/moment-timezone-utils/*. #174 (Tim Wood)

 * [Kashif] In meta data, filter coutries which don't have any timezones for them. eg: 'Bovet island' (kashif shamaz)


2015-01-13, Version 0.3.0
=========================

 * Add links to the changelog. (Tim Wood)

 * Version 0.3.0. (Tim Wood)

 * Add a hint when using an older version of moment with setDefault() (Tim Wood)

 * Renable default zone tests now that moment@2.9.0 is released. (Tim Wood)

 * Don't add an offset to timezone moments that were created from cloned moments. (Tim Wood)

 * Remove needsOffset tests for cloned moments. (Tim Wood)

 * Commenting out default tests until moment/moment#2054 lands (Tim Wood)

 * Failing tests for #135 (Tim Wood)

 * Add temporary wrapper for moment#utcOffset until it lands in moment core (Tim Wood)

 * Add tests for isSame() #127 (Alexander Zagumennikov)

 * Fix for error "stderr: maxBuffer exceeded", while running `data-zdump` grunt task. (kashif shamaz)

 * Rebuild metadata for all 2014 releases according to the new schema (Tim Wood)

 * Updates to the grunt task `data:meta`: 1. Pick "zone1970.tab" as its input source if available, defaults to zone.tab. (until 'tzdata2014f', only zone.tab was available, but now it's the deprecated version) 2. Output JSON of this task now has two hashes: "countries" and "zones" to facilitate consumers to deal much better with showing timezone choices. 3. Updated contribution docs to add info about "data-meta" grunt task. (kashif shamaz)

 * Update tests to use utcOffset instead of zone (Iskren Chernev)

 * Prefer moment.fn.utcOffset to moment.fn.zone (Iskren Chernev)

 * Add some basic tests for default timezone support. (elad)

 * Return the moment instance for chaining. (elad)

 * Add a missing semicolon. (elad)

 * Better approach for keeping timezone from @timrwood. (elad)

 * Add moment.tz.setDefault() and use timezone from object. (elad)


2014-11-12, Version 0.2.5
=========================

 * Version 0.2.5 (Tim Wood)

 * Update TZDB for 2014j (Tim Wood)


2014-10-27, Version 0.2.4
=========================

 * Changelog for 0.2.4 (Tim Wood)

 * Add data for 2014g and 2014h (Tim Wood)

 * Build for 2014i (Max Zavyrylin)


2014-10-20, Version 0.2.3
=========================

 * Version 0.2.3 (Tim Wood)

 * Build for for 2014h (Max Zavyrylin)


2014-09-04, Version 0.2.2
=========================

 * Version 0.2.2 (Tim Wood)

 * Whitespace and style changes (Tim Wood)

 * Build data and tests for 2014g (Tim Wood)

 * Add 2014f data. (Tim Wood)

 * Add in Tim's suggestions - cleanup one console.error (Patrick Hogan)

 * Add check for momentProperties to avoid uncaught exception (Patrick Hogan)


2014-08-02, Version 0.2.1
=========================

 * Version 0.2.1 (Tim Wood)

 * Fix add/subtract argument order (Tim Wood)

 * Support 2.8.1 with the _z and _a properties (Tim Wood)

 * Forward all moment.utc arguments from wrapper (Iskren Chernev)

 * Correctly register _z in momentProperties (Iskren Chernev)


2014-07-21, Version 0.2.0
=========================

 * Version 0.2.0 (Tim Wood)

 * Add an error message when timezone data has not been loaded. #106 (Tim Wood)

 * Add dependency on moment to bower.json #107 (Tim Wood)

 * Make links into actual Zone objects instead of just referencing the linked Zone. (Tim Wood)

 * Passing tests for configuring which offset to use during ambiguous or invalid offsets (Tim Wood)

 * Add failing tests for moving ambiguous input times forward. (Tim Wood)

 * Add failing tests for moving invalid input times forward. (Tim Wood)


2014-06-23, Version 0.1.0
=========================

 * Version 0.1.0 (Tim Wood)

 * Updating changelog for 0.1.0 (Tim Wood)

 * Add versioned data files to the ignored bower file list and add bower description. (Tim Wood)

 * Update package metadata and add npmignore (Tim Wood)

 * Use the develop branch of travis, not master (Tim Wood)

 * badges badges badges badges (Tim Wood)

 * Use 2010-2020 build as the main entry point for bower, update ignored files in bower.json #97 (Tim Wood)

 * Add `grunt build` task to inject data directly into the build files. (Tim Wood)

 * Add moment.tz.filterLinkPack and tests (Tim Wood)

 * Allow moment.fn.utc to clear the timezone flag #86 (Tim Wood)

 * Add check for whether the last item in the untils in filterYears is null to better mirror the actual data in data/unpacked/{version}.json (Tim Wood)

 * Include all of the meta comments, not just the first whitespace separated word. (Tim Wood)

 * Compile metadata using `grunt data-meta`. (Tim Wood)

 * Sort links alphabetically. (Tim Wood)

 * Add task to parse country, latitude, longitude, and comments metadata from zone.tab. (Tim Wood)

 * Add moment.tz.filterYears to subset data to a start and end year. (Tim Wood)

 * Merging in feature/parsing-rewrite (Tim Wood)

 * Use `moment.tz.load` instead of `moment.tz.add` to import initial data in Node. (Tim Wood)

 * Add `moment.tz.load` to import data in the {version:'2014e',zones:[],links:[]} format. (Tim Wood)

 * Compiling data/{packed,unpacked}/2014{a..e}.json (Tim Wood)

 * Build latest data (Tim Wood)

 * Add version to packed and unpack data objects. (Tim Wood)

 * Add moment.tz.createLinks to find zones that are identical except for their name. (Tim Wood)

 * Wrap moment-timezone-utils.js in the same UMD wrapper as moment-timezone.js (Tim Wood)

 * Add deprecation warning for moment.tz.zoneExists #94. (Tim Wood)

 * Removing tests for moment.tz.zoneExists(name), use !moment.tz.zone(name) instead (Tim Wood)

 * Move manipulate tests into tests/moment-timezone #94 (Tim Wood)

 * Change bower entry point to moment-timezone.js #89 (Tim Wood)

 * Add support for parsing into a timezone. (Tim Wood)

 * Switch to UMD (Tim Wood)

 * Move the travis badge to the same line as the title. (Tim Wood)

 * Update readme, move changelog to its own file, add contribution docs. (Tim Wood)

 * Add all 2014 data releases. (Tim Wood)

 * Fix download link for non-latest releases. (Tim Wood)

 * Remove unused grunt tasks and helpers, add logging to the build process. (Tim Wood)

 * Add data-download task and make whole process version aware. (Tim Wood)

 * Fix rounding errors (Tim Wood)

 * Add data-test grunt task to generate tests. (Tim Wood)

 * Remove eggert/tz submodule (Tim Wood)

 * Add data-pack and data-dedupe tasks (Tim Wood)

 * Add task to compress individual zdump files into one json file (Tim Wood)

 * Add data-zdump and data-zic tasks (Tim Wood)

 * Adding tests for moment.tz.names() (Tim Wood)

 * Cleaning up structure and adding passing link tests (Tim Wood)

 * Removing old version of the links tests (Tim Wood)

 * Add failing tests for links (Tim Wood)

 * Add some more tests for moment.tz.add (Tim Wood)

 * Add tests for moment.tz.add (Tim Wood)

 * Add tests for Zone(), Zone#_index, Zone#abbr, and Zone#offset (Tim Wood)

 * Add tests for packing bad input data (Tim Wood)

 * Add moment.tz.pack to the utils and add tests (Tim Wood)

 * Add packing of floating point numbers and tests (Tim Wood)

 * Adding test and utils files for base60 packing (Tim Wood)

 * Adding tests for packing base60 ints (Tim Wood)

 * Switching Zone to use unpack() (Tim Wood)

 * Adding tests for unpacking a string of data into an object of arrays (Tim Wood)

 * Passing tests for unpacking base 60 floats (Tim Wood)

 * Adding failing tests for parsing base 60 floats (Tim Wood)

 * Add tests for unpacking base 60 ints (Tim Wood)

 * Switch to a flat data format. (Tim Wood)


2014-04-20, Version 0.0.6
=========================

 * Uglify (Iskren Chernev)

 * Bump version to 0.0.6 (Iskren Chernev)

 * Multiple require('moment-timezone') receive undefined (Michael Ridgway)

 * Remove node 0.8 from build matrix (Iskren Chernev)

 * Use numberic month setter instead of string one (Iskren Chernev)

 * Add missing semicolon (Iskren Chernev)


2014-04-12, Version 0.0.5
=========================

 * Minify (Iskren Chernev)

 * Bump version to 0.0.5 (Iskren Chernev)


2014-04-12, Version 0.0.4
=========================

 * Properly bump version in moment-timezone.js (Iskren Chernev)

 * Bump version to 0.0.4 (Iskren Chernev)

 * Bump version of moment to 2.6.0 (Iskren Chernev)

 * Use ISO format when creating test moments (Iskren Chernev)

 * Bump dev dependencies versions (Iskren Chernev)

 * Prevent double loading of moment-timezone plugin (Iskren Chernev)

 * Add moment.tz.zoneExists (Iskren Chernev)

 * Set _z in momentProperties (Iskren Chernev)

 * Use new zone api for keeping the time (Iskren Chernev)

 * Use zone(z, false) to set the zone without adjusting time (Iskren Chernev)

 * Revert accidental merges into master (Iskren Chernev)

 * Fix for add/subtract when crossing a tz offset (Elliot Kroo)

 * Update .npmignore (Martin Frost)

 * Added .npmignore to ignore tests (Martin Frost)

 * check for module before window for browserify support (Mike Frey)

 * Drastically improve perf with memoize (Casey Foster)


2013-10-10, Version 0.0.3
=========================

 * Bump version to 0.0.3 (Iskren Chernev)


2013-10-10, Version 0.0.2
=========================

 * Bump version to 0.0.2 (Iskren Chernev)

 * Added bower configuration (Iskren Chernev)

 * allow newer versions of moment (Isaac Cambron)

 * merging master (Tim Wood)

 * moment.tz parses moments in the argument timezone (Adam Hull)

 * bumping nodeunit to restore testing on node 0.10 (Adam Hull)

 * Added Travis status image/badge (Andreas Savvides)

 * renaming to zones (Tim Wood)

 * adding links for backward and etcetera files #10 (Tim Wood)

 * fixes, build is ok now (Sven Tatter)

 * add method to get all TimeZoneSets (Sven Tatter)

 * updating package.json for #12 (Tim Wood)


2013-07-07, Version 0.0.1
=========================

 * First release!

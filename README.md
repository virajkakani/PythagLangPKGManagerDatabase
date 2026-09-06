# PPI database

This is a database for the libraries of the Pythag Language that have registered or been added to the Pythag Package Interface (ppi)
This database is alphabetically ordered based on the name of the .

No versions will be deleted from here unless they have malware

## Specifications for the row for your library:
* The dependencies file must be a link to a txt where the txt has all of the links to the dependencies of your library. Make sure **all** links to child and grandchild dependencies are written. **Do not make this dependencies file have the names of the dependencies or any other metadata.** (see exampledeps.md for more details)
* No entry may be named "name", "version", "links" or "dependencies file" or anything else that could confuse the engine.
* No spaces allowed anywhere ("math", "v0.0.1" must become "math","v0.0.1").
* Tabs (\t) must be between rows and commas should be between entries.
* You must use all columns but if you do not have any dependencies which aren't from the standard lib, just put "__NONE" as the entry (this works for both the columns "dependencies_file" and "dependencies_names_file". **Do not include any standard library headers in your deps file**

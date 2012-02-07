# About

This is a basic maven archetype for a casmi project.


# Usage


## install archetype on local

    $ cd [casmi-archetype]
    $ mvn install


## upload casmi.github.com

	$ cd [casmi.github.com]/maven-repo/casmi/casmi-archetype/0.1.0-SNAPSHOT
	$ cp ~/.m2/repository/casmi/casmi-archetype/0.1.0-SNAPSHOT/casmi-archetype-0.1.0-SNAPSHOT.* .
	
	$ cd [casmi.github.com]/maven-repo
	$ vi archetype-catalog.xml


## use on eclipse (m2eclipse)

* [Preferences...] -> Maven -> Archetypes -> Add Remote Catalog...
* Input "Catalog File" "http://casmi.github.com/maven-repo/archetype-catalog.xml
* [File] -> [New] -> [Project...] -> [Maven Project]
* [Select an Archetype] -> select the catalog -> check "Include snapshot archetypes"


# License

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License.

You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and limitations under the License.
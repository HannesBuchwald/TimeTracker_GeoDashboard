# TimeTracker Geo MainServer

This is a web based dashboard. It is part of the TimeTracker Ecosystem.
For more information about this project have a look at http://timetracker.cc.


## Functionality
This Dashboard is an interface to view recorded GeoDates.
In the TimeTracker ecosystem it is used to display the GeoDates from two sources.
One source is mobile Application with which is possible to track a Geo position.
The second source are weather datas form a mobile weather station.

How to get the actual data:
The script is pulling the Geo data from the Geo MainServer. There it gets
all the data which are stored in the database.

Features - flexible template built on active open source components
* Entirely client-side, can be hosted for free on [GitHub Pages](https://pages.github.com/)
* Built on the incredibly popular [Bootstrap](http://getbootstrap.com/) UI framework
* Maps via [Leaflet](http://leafletjs.com/), the leading open source JavaScript mapping library
* Interactive data table with sorting, searching, column toggling, and data export via the [Bootstrap Table](http://bootstrap-table.wenzhixin.net.cn/) plugin
* Advanced, interactive GeoJSON data querying that integrates [jQuery QueryBuilder](http://mistic100.github.io/jQuery-QueryBuilder/index.html) with [AlaSQL](http://alasql.org/)
* Advanced charting via [C3.js](http://c3js.org/), the D3-based reusable chart library


##Security
The website is protected with Crypto.js. In the source code is also a index.html
file which is not encrypted this can be used to do a own decryption.


## Hosting
It is recommended to host to dashboard on a own webserver.


## Demonstration
Under the following link a demo dashboard is initiated.
https://geo.timetracker.cc


## Team
Development
- Hannes Buchwald ([hannes@timetracker.cc](mailto:hannes@timetracker.cc))

Project Coordination
- Thomas Daum [thomas@timetracker.cc](mailto:thomas@timetracker.cc))


## License
The basic template of this GeoDashboard is from Fulcrum
and under the MIT License.

The content and extensions are from Hannes Buchwald
and under the GNU AGPLv3 license.

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

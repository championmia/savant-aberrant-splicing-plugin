# Introduction #

The plugin is designed to work with Savant genome browser <a href='http://genomesavant.com/savant/'>Savant</a> of v 2.0 and higher. The plugin contains all the source code, please feel free to modify it further for your needs.

# Details #

The plugin is based on modeling of splice site junctions with the <a href='http://www.biology-direct.com/content/1/1/10'>Bayesian splice site sensor</a> that has been found to have excellent sensitivity and specificity predicting splice sites compared to other sensor designs. Our plugin represents acceptors as red triangles and donors as blue or maroon colored (for GC non-canonical donors) triangles. The strength of a signal (how much signal triangle is filled with a color) characterizes its splicing competence. The stronger a signal, the more likely it flanks a true rather than cryptic exon.
The plugin also incorporated modeling of internal exons (note that only internal exons are currently modeled, the first and last exons have different splicing mechanisms) by the SpliceScan II <a href='http://www.biomedcentral.com/1471-2105/11/22/abstract'>program</a> .

Additional information on how to use the plugin is currently available from our <a href='http://prevmed.big.ac.cn/SplicingModeling.html'>web site</a>. Once you have questions please do not hesitate contacting me at `alexander<at>big.ac.cn`.

# License #

Licensed under the Apache License, Version 2.0. You may obtain a copy of the License at

> <a href='http://www.apache.org/licenses/LICENSE-2.0'><a href='http://www.apache.org/licenses/LICENSE-2.0'>http://www.apache.org/licenses/LICENSE-2.0</a></a>

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
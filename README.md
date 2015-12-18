

Apache Apex (incubating)
========================

Apache Apex is a unified platform for big data stream and batch processing. Use cases include ingestion, ETL, real-time analytics, alerts and real-time actions. Apex is a Hadoop-native YARN implementation and uses HDFS by default. It simplifies development and productization of Hadoop applications by reducing time to market. Key features include Enterprise Grade Operability with Fault Tolerance,  State Management, Event Processing Guarantees, No Data Loss, In-memory Performance & Scalability and Native Window Support.

##Documentation

Please visit the [documentation section](http://apex.incubator.apache.org/docs.html). 

[Malhar](https://github.com/apache/incubator-apex-malhar) is a library of application building blocks and examples that will help you build out your first Apex application quickly.

##Contributing

This project welcomes new contributors.  If you would like to help by adding new features, enhancements or fixing bugs, check out the [contributing guidelines](http://apex.incubator.apache.org/contributing.html).

You acknowledge that your submissions to this repository are made pursuant the terms of the Apache License, Version 2.0 (http://www.apache.org/licenses/LICENSE-2.0.html) and constitute "Contributions," as defined therein, and you represent and warrant that you have the right and authority to do so.
 
##Building Apex

The project uses Maven for the build. Run 
```
mvn install
``` 
at the top level. You can then use the command line interface (CLI) from the build directory:
```
./engine/src/main/scripts/dtcli
```
Type help to list available commands. 

Pre-built distributions (see [README](https://docs.datatorrent.com/installation)) are available from
https://www.datatorrent.com/download/

##Issue tracking

(Note that we will be moving to the Apache JIRA system soon.)

[Apex JIRA](https://issues.apache.org/jira/browse/APEXCORE) issue tracking system is used for this project.
You can submit new issues and track the progress of existing issues at https://malhar.atlassian.net/projects/APEX.

When working with JIRA to submit pull requests, please use [smart commits](https://confluence.atlassian.com/display/AOD/Processing+JIRA+issues+with+commit+messages) feature by specifying APEX-XXXX in the commit messages.
It helps us link commits with issues being tracked for easy reference.  And example commit might look like this:

    git commit -am "APEXCORE-1234 #comment Task completed ahead of schedule #resolve"

##License

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

##Contact

Please visit http://apex.incubator.apache.org and [subscribe](http://apex.incubator.apache.org/community.html) to the mailing lists.


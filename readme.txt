dsajkdhsadjkaidasdadasdadad fdsfsfsdfsdfsdfsfsdfdsfsfsdfsfcsf;dsj f;dasdadodsadasdasdsadfjldsdasdasdsjfkdslkjfsdfdsfsdsfsfdsadasdsada
fsdlkfjdsflkjsfkjksdasdsadasddsaldjfjdsfddsadfgdgdddsadrerewrwrdsdssdsadsadadasdsa
sdfdslfjsdlfjlkdsjfsddddddddSDasdasdasdddased
Fs'dfds;lfkdfsdsadsadasd
This dad;ad;s ftrete
This is my fixsssssed for DevOpsSchool.com....Fix for Taskggggg 55555  HON-1dsdasdasdaadas6666666
For any questions - Please email me at DevOps@RajeshKumar.gxyz/
# this isddd a fix og sdfljflld fjldsfjdsjfkdl;sdasdadddsdasd
# ========================NEXUS==============================

<distributionManagement>
	<repository>
		<id>tata</id>
		<name>Internal Releases</name>
		<url>http://13.127.163.182:8081/repository/scmgalaxy/</url>
	</repository>
 
	<snapshotRepository>
		<id>tata</id>
		<name>Internal Releases</name>
		<url>http://52.66.106.91:8081/nexus/content/repositories/snapshot/</url>
	</snapshotRepository>

</distributionManagement>


===============ARTIFACTORY=================
<distributionManagement>
	<repository>
		<id>rajesh</id>
		<name>Internal Releases</name>
		<url>http://13.127.94.210:8081/artifactory/list/rajesh-release/</url>
	</repository>
 
	<snapshotRepository>
		<id>rajesh</id>
		<name>Internal Releases</name>
		<url>http://13.127.94.210:8081/artifactory/list/rajesh-snapshot/</url>
	</snapshotRepository>

</distributionManagement>

=====================SETTING.XML=================================
   <server>
		<id>rajesh</id>
		<username>rajesh-user</username>
		<password>rajesh-user123</password>
</server>

=======================Setting.xml with Artifactory Setup======================
<mirror>
      <id>central</id>
      <name>Maven Repository Manager running on repo.mycompany.com</name>
      <url>http://13.127.94.210:8081/artifactory/list/group/</url>
      <mirrorOf>*</mirrorOf>
    </mirror>
    
    


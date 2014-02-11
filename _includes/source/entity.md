###Entity

~~~
<?xml version="1.0"?>
<doctrine-mapping xmlns="http://doctrine-project.org/schemas/orm/doctrine-mapping" xsi="http://www.w3.org/2001/XMLSchema-instance" schemaLocation="http://doctrine-project.org/schemas/orm/doctrine-mapping.xsd">
  <entity name="mainmodule-namespace\SampleEntity" change-tracking-policy="NOTIFY" schema="schema-name" table="table-name" repository-class="repository-class">
    <id name="id" type="integer">
      <generator strategy="AUTO"/>
    </id>
    <options>
      <option name="charset" value="charset"/>
      <option name="collate" value="collate"/>
      <option name="comment" value="comment"/>
      <option name="engine" value="engine"/>
      <option name="temporary" value="true"/>
    </options>
  </entity>
</doctrine-mapping>
~~~

Or go and see how to [do this in few clicks](http://frekr.github.io/ormcheatsheet/404).

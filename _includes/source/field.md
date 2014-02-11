###Field

~~~xml
  <entity name="SampleEntity">
    <id name="id" type="integer" column="column-name" column-definition="column-definition" precision="1" scale="1" version="true">
      <generator strategy="AUTO"/>
      <sequence-generator allocation-size="1" initial-value="1" sequence-name="sequence-name"/>
      <options>
        <option name="comment" value="comment"/>
        <option name="unsigned" value="true"/>
        <option name="version" value="version"/>
      </options>
    </id>
    <options>
      <option name="charset" value="charset"/>
      <option name="collate" value="collate"/>
      <option name="comment" value="comment"/>
      <option name="engine" value="engine"/>
      <option name="temporary" value="true"/>
    </options>
  </entity>
~~~

Or go and see how to [do this in few clicks](http://frekr.github.io/ormcheatsheet/404).

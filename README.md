<entry key="restEnabledSql.active">true</entry>

# Configuring the Maximum Number of Rows Returned from a Query
<entry key="misc.pagination.maxRows">1500</entry>

<entry key="jdbc.enableONS">true</entry>
<entry key= "jdbc.ONSConfig">nodes=racnode1:4200,racnode2:4200\nwalletfile=/oracle11/onswalletfile</entry>

<entry key="db.connectionType">customurl</entry>
<entry key="db.customURL">jdbc:oracle:thin:@(DESCRIPTION=(FAILOVER=ON)(ADDRESS_LIST=
                (LOAD_BALANCE=ON)(ADDRESS=(PROTOCOL=TCP)(HOST=prod_scan.example.com)(PORT=1521)))
                (CONNECT_DATA=(SERVICE_NAME=ISPRD)))|</entry>

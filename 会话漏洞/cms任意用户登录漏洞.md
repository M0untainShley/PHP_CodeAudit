444/admin_123,444test/admin_123



/interface/memebermain.php

```php
function in_center() {
    if ($this->CON['mem_isucenter']) {
        include_once admin_ROOT . 'public/uc_client/client.php';
    }
    parent::start_pagetemplate();
    parent::member_purview();
    $lng = (admin_LNG == 'big5') ? $this->CON['is_lancode'] : admin_LNG;
    $db_where = "userid=$this->ec_member_username_id AND username='$this->ec_member_username' ";
    $db_table1 = db_prefix . 'member AS a';
    $db_table2 = db_prefix . 'member_value AS b';
    $db_sql = "SELECT a.*,b.mvid,b.value FROM $db_table1 LEFT JOIN $db_table2 ON a.userid = b.userid  WHERE a.userid = $this->ec_member_username_id ";
    $rsMember = $this->db->fetch_first($db_sql);
    $rsMember['rankname'] = $this->get_member_purview($rsMember['mcid'], 'rankname');
    $userid = $rsMember['userid'];
    ......
```


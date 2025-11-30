---
title: "AutoTicketLinkName"
date: 2025-11-30T16:50:22+09:00
lastmod: 2025-11-30T16:50:22+09:00
slug: "AutoTicketLinkName"
draft: false
---

# AutoTicketLink definition

Reference: https://pukiwiki.osdn.jp/?AutoTicketLink

- jira https://site1.example.com/jira/browse/
  - AAA Project title $1
  - BBB Project title $1
- jira https://site2.example.com/jira/browse/
  - PROJECTA Site2 $1


 (Default definition) pukiwiki.ini.php
  = array(
   'title' => 'My JIRA - $1',
   'base_url' => 'https://issues.example.com/jira/browse/',
 );

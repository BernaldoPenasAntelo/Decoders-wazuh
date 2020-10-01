# Decoders-wazuh

This repository contains custom Decoders and rules for various Products that I have created for my own use.

Log fields where mapped to ECS (Elastic Common Schema) to integrate them with an **ELK stack** please review:
https://www.elastic.co/guide/en/ecs/current/index.html

----
Contents:

  - Paloalto Firewall Decoders and Rules
  - Sonicwall Firewall Decoders and Rules
  - Sophos Firewall Decoders and rules
  - TrendMicro DeepSecurity Decoders and Rules
  - TrendMicro ScanMail Decoders and Rules
  
----

In some cases existing decoder may be bypasssed with configuration, for example Sonicwall

 <decoder_exclude>0295-sonicwall_decoders.xml</decoder_exclude>



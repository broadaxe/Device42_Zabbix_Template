# Device42_Zabbix_Template
This is a sample template that works for Zabbix 4.X/5.X to poll the /healthstats of Device42 appliances. It
assumes this API is not password protected. It should be trivial to adapt it to a password or other
authentication mechanism.
- Import template to zabbix server;
- Optionally, create a Device42 Host Group and add your appliance(s) to it as well as the template;
- Assign the template to your appliances;
- ECheck 'Latest Data' to ensure that data is being collected;
- Check out the Graph and see the comparison between Total Memory vs Available Memory;

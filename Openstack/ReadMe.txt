1����openstack-status�ű��Ļ����������˼�أ��Ͳ���������ȥд��
check_openstack.sh ��ؽű�
openstack.cfg      zabbix�����ļ�
zbx_export_templates_Openstack.xml zabbix openstack ���еļ��ģ��

ʹ�ã�
UserParameter=Openstack.parameter[*],/usr/local/check_openstack/check_openstack.sh $1
UserParameter=Openstack.openstack-nova-api,/usr/local/check_openstack/check_openstack.sh openstack-nova-api
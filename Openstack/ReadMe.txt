1����openstack-status�ű��Ļ����������˼�أ��Ͳ���������ȥд��
check_openstack.sh ��ؽű�
openstack.cfg      zabbix�����ļ�

ʹ�ã�
UserParameter=Openstack.parameter[*],/usr/local/check_openstack/check_openstack.sh $1
UserParameter=Openstack.openstack-nova-api,/usr/local/check_openstack/check_openstack.sh openstack-nova-api
WestChamber alpha - Windows��ֲ˵��

��飺 
WestChamber��Windows��ֲ�汾�� 
����NDIS����������Microsoft��PassthruԴ�����WestChamber Linux verԴ������ɡ� 
������ĿDownloadҳ�����أ��� 


��ǰ���ȣ� 
�����DNS����������(gfw)��ZHANGģ�顣 


TODO: 
���CUIģ�顣����GUI�� 


����Windows�汾�� 
Wwindows XP-Windows 7������ͨ�á� 


ע�⣺ 
����ֲ�汾���ڸ��𲽵Ĳ��֣��ȶ��Ի�û�о������ģ��֤�� 
������������ʧ�ܿ��ܵ����޷���������ϵͳ�� 
���ڰ�װǰ�����Լ���Ҫ�����ݣ�������ϵͳ��ԭ������á� 
����޷�����ϵͳ�������Windows��ȫģʽ�������ķ�ʽж�ء� 


����˵�� 
�������ȷ���Լ�����ʲô���������ĵȴ������Ƴ������Ƶİ汾�� 

64λϵͳ - ����ǩ����
Windows 64λϵͳǿ��Ҫ��������������ǩ����
���ϣ������64λ�汾���ڰ�װ֮ǰ��
��ʹ�ø�����dseo13b�����ϵͳ��Test Mode��
Ȼ���ֶ���westchamber.sysǩ��(sign a system file)��

��װ˵���� 
����BindView�� 
��Install��ѡ��Service��ѡ��Ӵ��̰�װ��ѡ��driverĿ¼��netsf.inf�� 
���������δ������ǩ�������ڣ��㡺ȷ����/����Ȼ��װ���� 
֮���������������ڣ�����BindView��Service�б��ڣ�Ӧ�ÿ��Կ���westchamber driver����������˵����װ�ɹ��� 


ʹ��˵���� 
����DbgView��Capture - Capture Kernel�����ݼ�Ctrl + K���ɿ�����ʾ��Ϣ�� 
����޷�����������Ϣ���뽫DbgView�е�Capture - Enable Verbose Kernel Outputѡ��򿪡�

DNS�������� 
������ַ���DNSα���ݰ�ָ�Ƶİ���������ʾDetected GFW Poinsoned DNS data�������������� 


IPɸѡ�� 
������C�̸�Ŀ¼��ȡiplog.bin���ṹ���£� 
struct 
{ 
        unsigned int32 dwNum; 
        unsigned int32 big_endian dwIpAddress[dwNum]; 
} 


����ע��Ŀǰû��֧�ֶ�̬����/����iplog�����������Ҫ����iplog������ж��-��װ����������ϵͳ���� 
��װ���ڰ�����iplog.bin�Ǹ���WestChamber Linux�汾�ں���IP�б������ɣ�����Youtube������Google���� 
��IP��ַ�� 

ж��˵���� 
BindView -> Uninstall -> WestChamber Driver���ɡ� 


�κε���������顢BugReport�ȵȶ���ӭ������������(elysion51@gmail.com���� 

ת��״̬��
WestChamberWindowsĿǰ��3��֧��״̬��
NONE��TCPȫ�����У���IPLOG������IPLOGɸѡ����ALL��ȫ������ZHANG����
��������bin/wcwcontroller.exe���û�̬ת��״̬��

����Issue Report:
����������������ܵĻ����ṩ����ת���ļ���
����Windows\minidump�ļ����£�ϵͳ����������ġ�ϵͳ�Ѵ����ش����лָ������ڵġ���ϸ��Ϣ����Ҳ�У���
����ڰ�װ��û���κ���Ӧ���볢������ϵͳ��

��֪���������⣺
��Kaspersky��NDIS Filter�����ݡ�

���������Ϣ��
��·�ϴ���NAT�������нϴ��ʲ��ɹ���NAT���δ��ȫʵ��TCP��RFC�������ܵĻ��볢��ֱ����
westchamber.sys��Դ�������ϴ���SVN�� 
�����Ҫ���±��룬��ע��ʹ��checkedģʽ���Ա����������Ϣ�� 
westchamber.dll(��passthru.dll��������������BindView.exe��Դ�������Windows DDK���ҵ��� 
���⣬ϣ���и�����ϤWindows����������������NDIS�м��������������ʿ���ܹ��������뵽���������� 
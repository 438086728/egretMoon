# egretMoon
����Ϊ��������������һ�״������UI����,�û�����ͨ���޸���ɫֵ�õ��Լ�ϲ��������
���׷������Լ���һ�׶���moon.MoonEvent�¼�����������ı仯����
ʹ��ʱֻҪ��addEvent()��֡���仯�Ϳ��Եõ�����

# ���׷�����һЩ���õ������
* moon.BasicView				������
* moon.BasicButton 		������ť��ֻ������Ƥ����
* moon.MoreSkinButton 	���Ƥ����ť
* moon.RadioButtonBar 	��ѡ��Ĭ�������棬����ͨ��layout��������Ϊ��棩
* moon.CheckBoxBar			��ѡ��Ĭ�������棬����ͨ��layout��������Ϊ��棩
* moon.SliderBar				��������Ĭ�������棬����ͨ��layout��������Ϊ��棩
* moon.ProgressBar			��������Ĭ���ǲ���ʾ���ȵİٷֱȣ�����ͨ��showText������ʾ��
* moon.PanelBar				��壨�б���������������ɣ�
* moon.PanelMoreManager�����������������һ������л���ͬ��壩
* moon.MoonUI					�����кܶ෽������ֱ�ӵõ�Sprite��״����getRect,getCircle,getRoundRect�ȵ�
* moon.ShowLog					��ʾLOG�����ṩ���ַ���logֻ��ʾ���µ�һ��,logMessage����ʾ����
* moon.TipsManager			TIPS��ʾ�����絥����ť���ڰ�ť�Ϸ���ʾһ��TIPS˵��
* moon.MoonEvent				�¼�����,�ṩ�¼��㲥dispEvent,�¼�֡��addEvent,ɾ���¼�removeEvent
* moon.Label						ͳһ�ı����������

# �ӿ�
* ILayout ���������Ű�ķ������̳��˽ӿ�ILayout��������������type������interval���
�����ṩ����������Const.VERTICAL�ͺ��Const.HORIZONTAL
* IItem ������Ҫ���ӻ�ɾ���Լ����ļ��Ľӿڶ��̳д˽ӿ�
* IOnoff ���ؽӿ�

# ����˵��
* MoreSkinButton
		��ͬһ����ť����ʹ�ö��Ƥ��,�翪ʼ��Ϸ������һ�εȣ��Ϳ���һ����ť��ͬƤ����
		����MoreSkinButton��������toggleSwitchΪtrue��ʹ������״̬�Զ��л�
* ShowLogʹ��ʱ����Main�����е���һ��moon.showLog.getIns().init(this.stage);
Ȼ�����ֱ��ʹ��trace,��traceSimple���ֱ����logMessage������log����
* TipsManagerʹ��ʱ����Main�����е���һ��moon.TipsManager.getIns().init(this.stage);
Ȼ��ſ���ʹ��moon.TipsManager.getIns().simpleTips()



# egretMoon
����Ϊ��������������һ�״������UI����,�û�����ͨ���޸���ɫֵ�õ��Լ�ϲ��������
���׷������Լ���һ�׶���moon.MoonEvent�¼�����������ı仯����
ʹ��ʱֻҪ��addEvent()��֡���仯�Ϳ��Եõ�����

# ���׷�����һЩ���õ������
# ���ļ�MoonTheme.ts
* moon.BasicView				������
* moon.BasicButton 			������ť��ֻ������Ƥ����
* moon.MoreSkinButton 	���Ƥ����ť
* moon.RadioButtonBar 	��ѡ��Ĭ�������棬����ͨ��layout��������Ϊ��棩
* moon.CheckBoxBar			��ѡ��Ĭ�������棬����ͨ��layout��������Ϊ��棩
* moon.SliderBar				��������Ĭ�������棬����ͨ��layout��������Ϊ��棩
* moon.ProgressBar			��������Ĭ���ǲ���ʾ���ȵİٷֱȣ�����ͨ��showText������ʾ��
* moon.PanelBar					��壨�б���������������ɣ�
* moon.TabbarBar				ѡ����ļ�������MoreSkinButton��
* moon.PanelMoreManager	�����������������һ������л���ͬ��壩
* moon.MoonUI						�����кܶ෽������ֱ�ӵõ�Sprite��״����getRect,getCircle,getRoundRect�ȵ�
* moon.ShowLog					��ʾLOG�����ṩ���ַ���logֻ��ʾ���µ�һ��,logMessage����ʾ����
* moon.TipsManager			TIPS��ʾ�����絥����ť���ڰ�ť�Ϸ���ʾһ��TIPS˵��
* moon.MoonEvent				�¼�����,�ṩ�¼��㲥dispEvent,�¼�֡��addEvent,ɾ���¼�removeEvent
* moon.Label						ͳһ�ı����������
* moon.TabbarBar				tabbar��ť���
* moon.AlertBar					�ֶ��رյ���ʾ�򾯸�
* moon.AlertAutoBar			�Զ��رյ���ʾ�򾯸�
* moon.AlertRollBar			�����رյ���ʾ�򾯸�
* moon.GameLoad					��Ϸ�زļ���ʱ�Ľ���
* moon.MoonDisplayObject��ʾ����(���޸ı���ɫ��߿�)

# ͼƬ�Ĺ���ģ��
# ���ļ�MoonImage.ts
* moon.Image					  ������ͼƬ������
* moon.BasicContainer		����ͼƬ������ͳһ������ɾ��������һ���ȷ�����
* moon.ImageChartlet		ͼƬ��ͼ�ࣨ��һ��Сͼƴ��һ����ı���ͼ��
* moon.ImageAnimation		ͼƬ�����ࣨʹ��һ���Ŷ���ͼƬ�����������ࣩ
* moon.ImageLayout		  ͼ�񲼾��ࣨͼƬ���¾��л�����̨�������Ҷ�С���ص㣩

# ����С��Ϸ����ģ��
# ���ļ�MoonGame.ts
* moon.BasicGamePanel		��������Ϸ�߼�������
* moon.BasicGameStart		��������Ϸ��ʼ������
* moon.BasicGameOver		��������Ϸ����������
* moon.BasicGameSet			��������Ϸ���ô�����

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



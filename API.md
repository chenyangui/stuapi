STU API
=======

## ͨ��˵��
* �������APIʱ��accessToken�ѹ��ڣ�����http statusΪ401���û������µ�¼��

## 1.��ȡ�û���Ϣ
* ����������ȡ��ǰ�û���Ϣ
* URL��https://[domain]/services/api/profile/self
* ��������
* ����ֵ��
```{
	"id": "�û�id",
	"username": "�û���",
	"email": "�����ʼ�",
	"fullName": "����",
	"englishName": "Ӣ����",
	"logoUrl": "��ǰͷ��",
	"coverImage": "��ǰ����",
	��role��:���û���ɫ��, // studentѧ����faculty��ʦ
	"studentId": "ѧ��" //ѧ�����д��ֶ�
	��teacherId��:����ʦ��š� //��ʦ���д��ֶ�
}```
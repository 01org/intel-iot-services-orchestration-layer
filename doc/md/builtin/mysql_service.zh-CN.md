mysql����
================

#����
Ϊʹ�ø����÷���, ����Ҫ���Լ��ĵ����ϰ�װmysql, �������ú�������á�
����mysql���÷���,����Ҫ��ģ����Ӧ�������������������˿ڣ�mysql�û�
����mysql���룬Ȼ��������������SQL��伴�ɡ�

![](./pic/mysql_service.JPG)

#SQL���

## ����

### ����

��������

### ����

`������`: �ַ���.

`�˿ں�`: ����.

`���ݿ�`: �ַ���.

`�û���`: �ַ���.

`����`: �ַ���.

### ����

`SQL ���`: �ַ���.

### ���

`���`: �ַ���.

`��Ϣ`: �ַ���.

### ����

![](./pic/insert.JPG)

![](./pic/insert_info.JPG)

`������`: host.

`�˿ں�`: port.

`���ݿ�`: mysql database.

`�û���`: mysql username.

`����`: mysql password.

`SQL ���`:insert into student (id,name,profession) values (101,'xiaoming','CS')

`���`: result.

`��Ϣ`: 'connect succeed'

`����`: ����¼ (id:10,name:xiaoming,profession:CS)
�����student.

## ɾ��

### ����

ɾ����¼

### ����

`������`: �ַ���.

`�˿ں�`: ����.

`���ݿ�`: �ַ���.

`�û���`: �ַ���.

`����`: �ַ���.

### ����

`SQL ���`: �ַ���.

### ���

`���`: �ַ���.

`��Ϣ`: �ַ���.

### ����

![](./pic/delete.JPG)

![](./pic/delete_info.JPG)

`������`: host.

`�˿ں�`: port.

`���ݿ�`: mysql database.

`�û���`: mysql username.

`����`: mysql password.

`SQL ���`: delete from student where name='lihua'

`���`: result.

`��Ϣ`: 'connect succeed'.

`����`: ɾ��student����������lihua�ļ�¼.

## ����

### ����

��������

### ����

`������`: �ַ���.

`�˿ں�`: ����.

`���ݿ�`: �ַ���.

`�û���`: �ַ���.

`����`: �ַ���.

### ����

`SQL ���`: �ַ���.

### ���

`���`: �ַ���.

`��Ϣ`: �ַ���.

### ����

![](./pic/update.JPG)

![](./pic/update_info.JPG)

`������`: host.

`�˿ں�`: port.

`���ݿ�`: mysql database.

`�û���`: mysql username.

`����`: mysql password.

`SQL ���`: update student set profession='Physics' where name ='zihua'

`���`: result

`��Ϣ`: 'connect succeed'.

`����`: ��student����������zihua�ļ�¼��רҵ��ΪPhysics.

## ��ѯ

### ����

��ѯ����

### ����

`������`: �ַ���.

`�˿ں�`: ����.

`���ݿ�`: �ַ���.

`�û���`: �ַ���.

`����`: �ַ���.

### ����

`SQL ���`: �ַ���.

### ���

`���`: �ַ���.

`��Ϣ`: �ַ���.

### ����

![](./pic/query.JPG)

![](./pic/query_info.JPG)

`������`: host.

`�˿ں�`: port.

`���ݿ�`: mysql database.

`�û���`: mysql username.

`����`: mysql password.

`SQL ���`: select * from student where name='xiaoming'

`���`: result.

`��Ϣ`: `connect succeed`

`����`: ��ѯstudent����������xiaoming���ڼ�¼��������Ϣ.

## �������ݱ�

### ����

�������ݱ�

### ����

`������`: �ַ���.

`�˿ں�`: ����.

`���ݿ�`: �ַ���.

`�û���`: �ַ���.

`����`: �ַ���.

### ����

`SQL ���`: �ַ���.

### ���

`���`: �ַ���.

`��Ϣ`: �ַ���.

### ����

![](./pic/create table.JPG)

![](./pic/create_table_info.JPG)

`������`: host.

`�˿ں�`: port.

`���ݿ�`: mysql database.

`�û���`: mysql username.

`����`: mysql password.

`SQL ���`: create table student( id int not null, name char(20), profession char(20)).

`���`: result.

`��Ϣ`: 'connect succeed'

`����`: ����ѡ���ݿ��д���student���ݱ���id,name,profession��������. 

## ɾ�����ݱ�

### ����

ɾ�����ݱ�

### ����

`������`: �ַ���.

`�˿ں�`: ����.

`���ݿ�`: �ַ���.

`�û���`: �ַ���.

`����`: �ַ���.

### ����

`SQL ���`: �ַ���.

### ���

`���`: �ַ���.

`��Ϣ`: �ַ���.

### ����

![](./pic/drop table.JPG)

![](./pic/drop_table_info.JPG)

`������`: host.

`�˿ں�`: port.

`���ݿ�`: mysql database.

`�û���`: mysql username.

`����`: mysql password.

`SQL ���`: drop table student.

`���`: result.

`��Ϣ`: 'connect succeed'.

`����`: ����ѡ���ݿ���student��ɾ��.

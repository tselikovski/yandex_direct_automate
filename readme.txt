///////////////////////////////////////////////////////////////////////
/// Project: �������������� ���������� �������� Yandex.direct       ///
/// Name: ���������� �� ���������                                   ///
/// Version: 1.1.1                                                  ///
/// Author: ��������� ��������� �������������                       ///
/// License: GNU General Public License                   			///
/// Url: http://cloud-automate.ru                                   ///
/// Email: info@cloud-automate.ru                                   ///
/// Requirements: PHP >= 5.2.0                                      ///
/// Charset: WINDOWS-1251                                           ///
/// Last modified: 23.08.2013 13:57                                 ///
///////////////////////////////////////////////////////////////////////

���������� �� ���������: 

�������������� ���������� �������� Yandex.direct  - ��� ���������, ������� ��� ������� �� HTTP, ������� ��� CRONTAB ������������� ����������� �������� ������ � ��������� �������� Direct.yandex.ru

1) ���������� ����������� ��� ����� � ���� ���������� ����� �� �������� � ���������� PHP: index.php, config.php � yandex_direct_automate.php

2) ��������� �����������. 
   ���������� ���������������� ����������: https://oauth.yandex.ru/client/new
   ����������� ������ ����������. ���������� �����: 
   ��������: �����
   �����: ������ ������.������ � ������ ������� �������:  ������������� API ������.������� 
   ��������� ���� �� �������. 
   ����� ��������� "�������". 
   �� ����������� �������� ���������: 
	- Id ����������, ��� ���������� �������� � "client_id" � ������� config.php
	- ������ ����������, ��� ���������� �������� � "client_secret" � ������� config.php

3) ���������� �������� ��������� � ���������������� ����� config.php 
 ������������ ����: 
 - "login" - ����� �� �������� yandex (�� ��� ����� @yandex.ru � �����)
 - "password" - ������ �� �������� yandex
 - "client_id" - �������� ����� 2.
 - "client_secret" - �������� ����� 2.
 
4) ��������� � CRONTAB ��� ������� ��������� ���� index.php � ���������� ������� ������ ������ ��� ����������� ������ � ������ �� HTTP ����� index.php
������ CRONTAB: * * * * * /usr/bin/php ~/���_����/www/�����_�_����������/index.php
������ HTTP: http://���_����/�����_�_����������/index.php

5) � ���������� �������� ������.������ � ������ "���������" ������� "��������� ��������� �������".

��������� ����������: 
- PHP 5.2.0 � ����
# ��� ����� ����� � GIT
---

## �������������� �����������

**������� ����� ������������ � git init**

����� Git ����� ����������� ��������� � �������, ����� � ������� ����� ������� ����� ������� **Git-������������**.
��� ����� ������� ������������� � �� � ������ �������:
```
git init
```

**����������� �����, ���� ���-�� ����� �� ���, � rm -rf .git**

���� �� �������� ������� Git-������������ �� �� �����, � ����� �����������. ��� ����� ����� ������� ������� �������� .git.
```$ cd <����� � ������������> # ������� � �����
$ rm -rf .git # ������� �������� .git 
```

**��������� ��������� ����������� � git status**

����� ������������� ����������� ��������� ������� git status � ��� ���������� ������� ��������� �����������. 


## ���������� ������ � �����������

**����������� ����� � ���������� � git add**

��� ���������� ������ � Git ����������� �������:
```
$ git add --all # ����������� � ���������� ��� ����� � �����������
$ git add <��� �����> # ����������� � ���������� ��������� � <> ����
``` 
## ������
������� ������ ����� �������� **git commit** c ������ **-m**, ������� ����������� ������� ���������.

```
$ git commit -m '��� ������ ������!' 
```
����� ������� Enter ������� ������ ������ ����� ��������� � ����������� � ���������� ��� ������ ������!. ������ (�� �������� ������� git commit) � ��� �� ���� ������ ������ � �� ���������.

## ���������� ���������� � ��������� ����������� � �������������

��������� �� �������� ��������� �����������, �������� ��� SSH � ���������� URL. ������ ������ �������� ������� ��� ���������.
�������� �������, ��������� � ������� ���������� ����������� � ������� ������� **git remote add**

```
$ cd ~/dev/first-project
$ git remote add origin git@github.com:%���_��������%/first-project.git 
```
origin (����. ���������) � ����������� ���������, � ������� �������� ����� ���������� � �������� ��������� ����������� (������ ����� ����������� ����). ��� ����������� �������� ������.


**���������, ��� ����������� �������, � git remote -v**
```
$ git remote -v
origin    git@github.com:%���_��������%/%���-�������%.git (fetch)
origin    git@github.com:%���_��������%/%���-�������%.git (push) 
```


**��������� ��������� �� �������� ����������� � git push**
� ������ ��� ��� ������� ����� ������� � ������ -u � ����������� origin (��� ��������� �����������) � main ��� master (�������� ������� �����). ���� -u ������ ��������� ����� � ���������� ��������. ��� �� ��������� ��������� � �������� �����������, ��� �� � ����� ����� ������������� ������� �����.

```
$ git push -u origin main # ���� ������� ������� � ������, ���������� 
                          # �������� main �� master. 
```

� ���������� ����������� ������� 
```
$ git push
```
						  
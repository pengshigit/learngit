��װ��ɺ󣬻���Ҫ���һ�����ã������������룺

$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"

���ԣ�����һ���汾��ǳ��򵥣����ȣ�ѡ��һ�����ʵĵط�������һ����Ŀ¼��

$ mkdir learngit
$ cd learngit
$ pwd
/Users/michael/learngit

�ڶ�����ͨ��git init��������Ŀ¼���Git���Թ���Ĳֿ⣺

$ git init
Initialized empty Git repository in /Users/michael/learngit/.git/

һ��Ҫ�ŵ�learngitĿ¼�£���Ŀ¼Ҳ�У�����Ϊ����һ��Git�ֿ⣬�ŵ������ط�Git������Ҳ�Ҳ�������ļ���

�ͰѴ���ŵ�������Ҫ3����ȣ���һ���ļ��ŵ�Git�ֿ�ֻ��Ҫ������

��һ����������git add����Git�����ļ���ӵ��ֿ⣺

$ git add readme.txt
ִ����������û���κ���ʾ����Ͷ��ˣ�Unix����ѧ�ǡ�û����Ϣ���Ǻ���Ϣ����˵����ӳɹ���

�ڶ�����������git commit����Git�����ļ��ύ���ֿ⣺

$ git commit -m "wrote a readme file"
[master (root-commit) cb926e7] wrote a readme file
 1 file changed, 2 insertions(+)
 create mode 100644 readme.txt

git commit����ִ�гɹ��������㣬1���ļ����Ķ�����������ӵ�readme.txt�ļ������������������ݣ�readme.txt���������ݣ���

ΪʲôGit����ļ���Ҫadd��commitһ�������أ���Ϊcommit����һ���ύ�ܶ��ļ�����������Զ��add��ͬ���ļ������磺

$ git add file1.txt
$ git add file2.txt file3.txt
$ git commit -m "add 3 files."




Git is a version control system.
Git is free software.
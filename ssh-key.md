##本地生成ssh-key
1. ssh-keygen -t rsa -C "dfchong@sina.com"
2. 输入github秘码
3. 生成文件在：
    ~/.ssh/id_rsa
    ~/.ssh/id_rsa.pub
4. 进入github.com
5. Account Settings
5. SSH Keys
5. add ssh key
    title: 自由起名
    key: *.pub文件的内容复制到此处
6. 测试是否成功
    ssh -T git@github.com
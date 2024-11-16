Nesa是轻量级的第1层区块链，使用链上ZKML对需要高度隐私、安全和信任的查询执行关键的AI推理。 — — rootdata
官方明确说明运行节点会赚取$NES
![14051731770009_ pic](https://github.com/user-attachments/assets/af48badb-a0ba-418b-bbe8-b2d83305734e)

# 最低系统要求
CPU：多核处理器
内存：最低 4 GB RAM
存储空间：50 GB 可用磁盘空间（或更多，具体取决于您想要供电的模型的大小）

# 教程
在 HuggingFace 上注册和设置 API 密钥 https://huggingface.co/
![441731766374_ pic](https://github.com/user-attachments/assets/271ab74a-0552-4683-a808-c0c65227d35b)

![451731766384_ pic](https://github.com/user-attachments/assets/55f763cf-be32-4d97-a5a2-5c09cebda796)

![461731766420_ pic](https://github.com/user-attachments/assets/edcf15e5-2327-470f-865c-ce2138a83bde)

把hf_*开头的 API 密钥记住 后面要用

然后下载leap钱包
```shell
https://chromewebstore.google.com/detail/leap-cosmos-wallet/fcfcfllfndlomdhbehjjcoimbgofdncg?hl=zh-CN&utm_source=ext_sidebar
   ```
到这里链接钱包后添加nesa测试网 然后把私钥记住 后面要用
```shell
https://node.nesa.ai/
   ```
链接服务器后输入
```shell
  wget -O nesa.sh https://raw.githubusercontent.com/GzGod/nesa/refs/heads/main/nesa.sh && sed -i 's/\r$//' nesa.sh && chmod +x nesa.sh && ./nesa.sh
   ```
后续会出现几个要选的
我已经把官方的包汉化了 按步骤来即可
后面再按几次确定就行了
第一次启动非常慢 成功后会显示successfully

之后可以选择在脚本里查看id

或者使用
```shell
cat ~/.nesa/identity/node_id.id
   ```

然后去节点面板查询你的节点状态
```shell
https://node.nesa.ai
   ```

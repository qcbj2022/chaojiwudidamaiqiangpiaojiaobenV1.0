# 超级无敌大麦抢票脚本 V1.0

## 简介

本项目提供了一个自动无延时抢票脚本，支持在大麦网（大麦APP）上进行演唱会票的抢购。该脚本支持人员、城市、日期场次、价格选择，并能够自动提交订单。

## 环境要求

- 需要安装 Appium Server & Client 环境。

## 使用步骤

1. **安装 Appium 环境**：
   - 请确保你已经安装了 Appium Server 和 Client。

   2. **进入大麦网**：
      - 打开大麦网，选择你需要抢票的演唱会。

      3. **修改配置文件**：
      4.    - 根据下图的标注对配置文件 `config.json` 进行修改：
           - `index_url`：大麦网的地址，无需修改。
                - `login_url`：大麦网的登录地址，无需修改。
                     - `target_url`：用户需要抢的演唱会票的目标地址，待修改。
                          - `users`：观演人的姓名，观演人需要用户在手机大麦APP中先填写好，然后再填入该配置文件中，待修改。
                               - `city`：城市，如果用户需要抢的演唱会票需要选择城市，请把城市填入此处。如无需选择，则不填。
                                    - `date`：场次日期，待修改。
                                         - `price`：票档的价格，待修改。
                                              - `if_commit_order`：是否要自动提交订单，改成 `true`。

                                              4. **启动脚本程序**：
                                                 - 进入项目目录：
                                                      ```bash
                                                           cd damai_appium
                                                                ```
                                                                   - 运行脚本：
                                                                        ```bash
                                                                             python3 damai_appium.py
                                                                                  ```

                                                                                  ## 注意事项

                                                                                  - 请确保在运行脚本前，所有配置信息已经正确填写。
                                                                                  - 观演人的姓名需要在大麦APP中提前填写好。
                                                                                  - 确保 Appium 环境已经正确安装并运行。

                                                                                  ## 贡献

                                                                                  欢迎大家贡献代码，提出问题和建议。

                                                                                  ## 许可证

                                                                                  本项目采用 [MIT 许可证](LICENSE)。

                                                                                  ## 下载链接
                                                                                  [超级无敌大麦抢票脚本V1.0](https://pan.quark.cn/s/bcb9c251633a) 

                                                                                  (备用: [备用下载](https://pan.baidu.com/s/1VH_cYVJG_2dXMQmA11EZOQ?pwd=1234))

                                                                                  ## 说明

                                                                                  该仓库仅用于学习交流，请勿用于商业用途。

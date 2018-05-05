
## 下列为结果文件
- Log_screenshot.png 运行成功后的log输出截图
- create_data.py 生成TF record 的脚本
- output.png 运行inference.py后的结果图
- ssd_mobilenet_v1_pets.config pipeline的配置文件
- tensorboard_eval_result1.png tensorboard上 eval的结果截图
- tensorboard_eval_result2.png 同上

## 心得
当我们需要使用finetune模型来进行物体检测时，我们需要
- 1. 选择合适的model zoo
- 2. 修改现有的model zoo提供的pipeline config文件
- 3. 将我们需要训练的数据集生成tfrecord
- 4. 合理使用tensorboard监控模型训练过程和评估结果
- 5. 其实总而言之，就是在现有的已经非常强大的框架下，修改一些脚本和配置

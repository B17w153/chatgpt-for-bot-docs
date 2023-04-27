# 🎤 文字转语音

这个章节将介绍如何让你的机器人在回复你的时候带上一条语音消息。 &#x20;

语音功能支持的配置项：

```toml
[text_to_speech]
# 语音转文字

# 是否默认开启文字转语音
always = false
# 默认音色
# 此选项和你使用的引擎有关
default = "zh-CN-XiaoyouNeural"

#引擎
engine = "edge"
```



要想开启语音功能，你还需要配置语音引擎。

目前我们支持两种不同的语音驱动引擎，分别为：微软 Azure TTS 和 VITS。

|      | Azure TTS          | VITS              | Edge TTS               |
| ---- | ------------------ | ----------------- | ---------------------- |
| 费用   | 新用户免费 200 美元，按字数收费 | 免费                | 免费                     |
| 音色   | 仅网站中列出的可用音色        | 可用使用自己训练的音色       | 比 Azure TTS 少一点        |
| 配置要求 | 能上网就行              | 可能强劲的 CPU 或者需要显卡  | 能上网就行                  |
| 磁盘占用 | 基本没有               | 至少为 3GB，主要取决于音色数量 | 基本没有                   |
| 速度   | 超快                 | 取决于服务器配置          | 超快                     |
| 稳定性  | 极高                 | 有时候可能会花很久         | 挺高                     |
| 限制   | 不支持混合不同的语言         | 一次说话不能超过150字      | 需要安装 ffmpeg、不支持混合不同的语言 |

如果你想使用 Edge TTS 的语音功能，请阅读：

{% content-ref url="edge-tts-yu-yin-jie-ru-jiao-cheng.md" %}
[edge-tts-yu-yin-jie-ru-jiao-cheng.md](edge-tts-yu-yin-jie-ru-jiao-cheng.md)
{% endcontent-ref %}

如果你想使用 Azure TTS 的语音功能，请阅读：

{% content-ref url="azure-tts-yu-yin-jie-ru-jiao-cheng.md" %}
[azure-tts-yu-yin-jie-ru-jiao-cheng.md](azure-tts-yu-yin-jie-ru-jiao-cheng.md)
{% endcontent-ref %}

如果你想使用 VITS 的语音功能，请阅读：

{% content-ref url="vits-yu-yin-jie-ru-jiao-cheng.md" %}
[vits-yu-yin-jie-ru-jiao-cheng.md](vits-yu-yin-jie-ru-jiao-cheng.md)
{% endcontent-ref %}

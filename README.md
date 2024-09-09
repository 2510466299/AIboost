# AIboost
使用ai应用来自我精进
## AI Boost学习方法论

从造纸术的出现，到电脑硬盘，知识的存储变得越来越容易，获得知识的途径也变得更丰富，所以有人说未来的知识越来越廉价了，我们还需要学知识吗？我们的回答还是需要，但往后我们不再是以学习知识为导向，因为知识本身已经越来越容易获取 ，这不该再成为一个阻碍，我们应该转变方向，以解决问题为导向，想要更好的解决问题，那么我们就应该学会如何提出问题，我们提出问题的质量取决于我们脑子里装了什么东西，如果我们脑子里知识很多，我们能借助更好的工具，我们也能提出更准确更好的问题。

在AI大模型出现之后，因为它的大脑里面有许多知识，他能辅助我们提出很多很好的问题，那么接下来，我们分享一个使用LLM来进行陌生领域学习与提问的方法论。

以下是使用LLM来学习和提问的流程：

那么接下来，我们分享一个使用LLM来进行陌生领域学习与提问的方法论。

![img](https://typora-pic-1-1329122223.cos.ap-guangzhou.myqcloud.com/blog/clip_image002.jpg)

以下使用‘golang后端开发’这个领域为例子：

首先，在大模型（以chat-gpt为例）按照模板提问，模板prompt：“我是一名golang后端开发领域的小白，请告知我在该领域必须掌握的100个基础概念，并给出每个概念的详细解释。“

![image-20240831014306922](https://typora-pic-1-1329122223.cos.ap-guangzhou.myqcloud.com/blog/image-20240831014306922.png)

……以下省略剩余部分（如果LLM没有输出数量的基础概念，你可以在prompt中输入‘继续输出’)。

在我们了解相关领域的基础概念之后，我们能够利用大模辅助我们提出二十个相关领域的元问题。

模板prompt“我想深入全面的学习了解“golang后端开发”相关的知识我应该问你什么问题?请至少列出20个。”

![image-20240831014327844](https://typora-pic-1-1329122223.cos.ap-guangzhou.myqcloud.com/blog/image-20240831014327844.png)

（此处截图有所省略）

在收集到20个元问题后，我们可以将其存放在我们设置的思维导图中（这里推荐亿图）。

![image-20240831014402235](https://typora-pic-1-1329122223.cos.ap-guangzhou.myqcloud.com/blog/image-20240831014402235.png)

那么我们在得知这些元问题后，我们需要使用能够输出信息来源的LLM应用来搜索相关问题，例如（perplexity，kimi，秘塔等）。在这些应用中搜索出来的答案都是有明确的信息来源，具有较高的可信度。---（如果使用perplexity建议使用英文进行搜索，以下为了阅读流畅，使用中文进行演示）

此处我们在perplexity中使用上述最后一个元问题“Golang 在微服务架构中通常是如何被应用的？“进行演示。

![img](https://typora-pic-1-1329122223.cos.ap-guangzhou.myqcloud.com/blog/clip_image010.jpg)

![img](https://typora-pic-1-1329122223.cos.ap-guangzhou.myqcloud.com/blog/clip_image012.jpg) 

![img](https://typora-pic-1-1329122223.cos.ap-guangzhou.myqcloud.com/blog/clip_image014.jpg)

在此类搜索型LLM应用中，其搜索结果最后往往有相关问题，我们可以将这些相关问题集合在我们的思维导图中。

![image-20240831014415948](https://typora-pic-1-1329122223.cos.ap-guangzhou.myqcloud.com/blog/image-20240831014415948.png)

由此，我们可以由20个元问题扩展到120个问题，在这120个问题的提问与学习中，我们还可以使用特定的prompt来使得LLM成为我们在特定问题上的专属导师。

特定的prompt是由github上的开源提供：[Mr.-Ranedeer-AI-Tutor/Mr_Ranedeer.txt at main · JushBJJ/Mr.-Ranedeer-AI-Tutor (github.com)](https://github.com/JushBJJ/Mr.-Ranedeer-AI-Tutor/blob/main/Mr_Ranedeer.txt)

使用特定的prompt之后，我们将问题中想要详细了解和测试的内容进行计划：

以下我们使用子问题“如何在Golang中实现微服务的自动化扩缩容“来进行演示：

输入特定的prompt后，LLM会给出下述回答：

![image-20240831151119593](https://typora-pic-1-1329122223.cos.ap-guangzhou.myqcloud.com/blog/image-20240831151119593.png)

为了方便教学，我们可以将语言切换为中文。

![img](https://typora-pic-1-1329122223.cos.ap-guangzhou.myqcloud.com/blog/clip_image018.jpg)![img](https://typora-pic-1-1329122223.cos.ap-guangzhou.myqcloud.com/blog/clip_image020.jpg)![img](https://typora-pic-1-1329122223.cos.ap-guangzhou.myqcloud.com/blog/clip_image022.jpg)![img](https://typora-pic-1-1329122223.cos.ap-guangzhou.myqcloud.com/blog/clip_image024.jpg)

![image-20240831151252108](https://typora-pic-1-1329122223.cos.ap-guangzhou.myqcloud.com/blog/image-20240831151252108.png)](https://typora-pic-1-1329122223.cos.ap-guangzhou.myqcloud.com/blog/clip_image026.jpg)

剩余测试内容在下述链接，如有需要可转移到链接内了解：https://chatgpt.com/share/6c22ec8b-2202-474b-9261-9d4ea57e4916

好了，到这里我们也就完成使用LLM进行提问，学习，测试的闭环啦！
恭喜你，在个人精进的道路上更进一步！

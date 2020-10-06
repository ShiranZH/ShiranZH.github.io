# About Me

I'm Shiran Zhang (张石然 in Chinese), currently a senior undergraduate student in [Peking University](http://english.pku.edu.cn/) (PKU), majoring in Computer Science and Philosophy. I'm expected to graduate in 2021.

## Education

<div align="left">
    <strong><a href="http://english.pku.edu.cn/">Peking University</a>, Beijing, China (Sep. 2017 - Jun. 2021)</strong>
    <ul>
        <li>Bachelor of Science (B.S.), Computer Science</li>
        <li><a href="https://cs.pku.edu.cn/English/Home.htm">Department of Computer Science and Technology</a></li>
        <li><a href="http://eecs.pku.edu.cn/Home/HOME.htm">School of Electronics Engineering and Computer Science</a></li>
    </ul>
</div>

<div align="left">
    <strong>Peking University (Second Major), Beijing, China (Sep. 2019 - Jun. 2021)</strong>
    <ul>
        <li>Bachelor of Philosophy (B.P.), Philosophy</li>
        <li><a href="https://en.phil.pku.edu.cn/">Department of Philosophy and Religious Studies</a></li>
    </ul>
</div>


## Experience

<div align="left">
    <strong>Alibaba Cloud Computing Company, Hangzhou, China (Jun. 2020 - Sep. 2020)</strong>
    <br />Software Development Engineer Intern, Enterprise Mobile Application Studio (EMAS)
    <ul>
        <li>Removed <i>Object Storage Service</i> during scaffold generation on DevOps Private Cloud</li>
        <li>Integrated monitoring capability in pipeline construction on DevOps Public Cloud</li>
    </ul>
</div>

# Archives

### Computer Science

{% for doc in site.docs.cs %}
{{ doc.date | date:"%Y-%m"}} {{doc.title}} \[[LINK](/docs/cs/{{ doc.title }}.md)\]

2020-10 阅读笔记：Prometheus监控实战 \[[NOTE](/docs/cs/阅读笔记：Prometheus监控实战.md)\]

### Philosophy

2019-11 民间信仰的流变与神灵的多元性——以金泽镇诸神信仰为例 \[[PDF](/docs/phil/民间信仰的流变与神灵的多元性——以金泽镇诸神信仰为例.pdf)\]

### Poetry & Prose

{% for doc in site.docs.poems %}
{{ doc.date | date:"%Y-%m"}} {{doc.title}} \[[LINK](/docs/poem/{{ doc.date }}-{{ doc.title }}.md)\]

2020-08 雨 \[[LINK](/docs/poem/2020-08-雨.md)\]

2020-03 暗物 \[[LINK](/docs/poem/2020-03-26-暗物.md)\]

2019-09 简单快乐 \[[LINK](/docs/poem/2019-09-14-简单快乐.md)\]

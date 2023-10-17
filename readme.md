### 本项目纯本地运行
### 数据展示
<table>
    <thead>
        <tr>
            <th colspan="4">处理1200张图片数据</th>
        </tr>
        <tr>
            <th>分辨率</th>
            <th>cpu</th>
            <th>用时</th>
            <th>单张耗时(秒)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="2">
                1920 * 1280
            </td>
            <td>R7-5800H</td>
            <td>00:11:51</td>
            <td>0.5925</td>
        </tr>
        <tr>
            <td>i7-7700HQ</td>
            <td>00:18:24</td>
            <td>0.92</td>
        </tr>
        <tr>
            <td rowspan="2">
                6000 * 4000
            </td>
            <td>R7-5800H</td>
            <td>01:50:54</td>
            <td>5.545</td>
        </tr>
        <tr>
            <td>i7-7700HQ</td>
            <td>02:57:49</td>
            <td>8.89</td>
        </tr>
    </tbody>
</table>

### 注意事项
0.图像资源仅支持png和jpg,MIME:image/jpeg,image/png
1.选择的文件夹内不要包含子文件夹
2.程序处理图像时进行其他操作会影响处理速度
3.切换tab或者浏览器最小化可能会导致程序暂停
4.试了下Worker,但cpu与内存资源占用极高,用户体验不咋地
### 仍有很多地方需要优化,如果你是一名技术开发人员,可以用你熟悉的语言提pr,以实现最优效果
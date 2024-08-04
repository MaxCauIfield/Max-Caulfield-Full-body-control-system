# Max Caulfield-全身控制系统第三版
## V0.1.3 第三版 发布于2024年8月5日
![_preview_00000](https://github.com/user-attachments/assets/09a8e1b3-17d2-454e-9fc3-3b8c8ceefc8f)
   本系统是基于CC4角色为基础（旧版基于Blender中的骨骼和形态键），为Max Caulfield（Life is strange1）创建的全身控制系统
##### 它包括：
<p>⭐标准的Max Caulfield CC4字符角色，兼容大多数动作捕捉系统以及面部捕捉系统</p>
<p>⭐支持导出几乎所有受支持的3D格式，可与大部分DCC软件和游戏引擎无缝连接</p>
<p>⭐具有AAA级品质的标准2K PBR模型和自由的体型控制系统</p>
<p>⭐兼容Adobe Mixamo动画库和诺伊腾动作捕捉系统,支持一键上传至Sketchfab</p>
<p>⭐简单的面部和身体运动导演，自由装配系统以及兼容软件强大的模型库</p>
<p>⭐无需学习任何dcc软件，脸部和身体均可独立、自然的控制</p>
   
   运动导演功能在旧版为形态键，它包括脸部和身体两部分，（旧版脸部动作由Blender中的形态键来控制其脸部表情），支持控制包括眉毛，眼睛，鼻子，嘴巴，舌头，睫毛等，并为其设置了脸部相应形态键的最大值，此分支仅兼容CC4以上的版本（旧版兼容Blender3.4-3.6），具体版本兼容列表请参阅下方说明，你可以通过Reallusion 或Blender官方网站下载受支持的软件，并修改和制作其表情动作，有关于详细的教程说明，已在BiliBili，Youtube，西瓜视频，抖音等平台详细描述，你可通过参阅有关信息来获取如何使用它，如果你并不了解其实际用途，请不要更改其相关的值，以免出现问题。!

注意：此文档中的“旧版”指的是0.1.2及之前的版本
   
![image](https://github.com/user-attachments/assets/d63a0b11-0088-4364-9bf7-55ed53a9b002)

本作品授权下Creative Commons 署名-非商业性使用-相同方式共享 4.0 国际，使用此项目请遵守CC-BY-NC-SA协议，有关于此协议的详细信息，请访问https://creativecommons.org/licenses/by-nc-sa/4.0/

项目作者有权更改，撤销，重新分发其相关许可证协议并保留权利归属

   ## 版本兼容列表
<table width="100%" border="1">
  <tbody>
    <tr>
      <td>版本</td>
      <td>兼容</td>
      <td>更新时间</td>
      <td>模型外观</td>
      <td>控制系统作者</td>
    </tr>
      <tr>
      <td>v0.1.3</td>
      <td>Character Creator v4.3</td>
      <td>2024年8月5日</td>
      <td>Max Caulfield (Butterfly)</td>
      <td>Alice的AX400</td>
    </tr>
    <tr>
      <td>v0.1.1</td>
      <td>Blender 3.4</td>
      <td>2023年5月16日</td>
      <td>Max Caulfield (Butterfly)</td>
      <td>Alice的AX400</td>
    </tr>
    <tr>
      <td>v0.1.2</td>
      <td>Blender 3.6</td>
      <td>2023年7月23日</td>
      <td>Max Caulfield (Underwear)</td>
      <td>Alice的AX400</td>
    </tr>
    <tr>
      <td>v0.1.1 Remastered</td>
      <td>Blender 3.6</td>
      <td>2023年7月23日</td>
      <td>Max Caulfield (Butterfly)</td>
      <td>Alice的AX400</td>
    </tr>
  </tbody>
</table>

------------------------------------------------------
# 以下是其旧版本（Blender版本）的历史更新日志
## The following is the historical update log of its old version (Blender version)
# Max Caulfield-全身控制系统第二版
## V0.1.2 第二版 发布于2023年7月23日
[无标题111](https://user-images.githubusercontent.com/61368414/235973174-15110931-13d0-4702-81d1-53433a60a89d.png)
   
# Max Caulfield-全身控制系统第一版
## V0.1.1 Remastered 重置版 发布于2023年7月23日
###   已知问题：
####   -相关贴图资源未打包在Blend文件中，此问题已修复
## V0.1.1 第一版 发布于2023年5月3日
###   已知问题：
####   -在使用面部捕捉软件为Max Caulfield创建表情动画时，如果其眉毛进行了变动，会出现眼睛过大的情况，此问题可以通过关闭问题形态键来解决，此问题将会在下一个版本中修复。
####   ![QQ图片20230504000055](https://user-images.githubusercontent.com/61368414/235972815-4de50b8c-0b3d-4944-b257-3c34a7b952e8.png)
## V0.1.0 内测版 发布于2023年5月1日 暂未公布其分支
###   已知问题：
####   -在控制Max Caulfield的头部进行旋转（或导入其他动画或动作捕捉软件时候，Max Caulfield的脸部会产生拉伸情况，此问题已在V0.1.1版本中修复。
#####  ![QQ图片20230503235825](https://user-images.githubusercontent.com/61368414/235971809-85d0cd8b-a5d8-4b95-80e9-edf941f7aaee.png)
####   -如果使用FBX形式导入此模型，或者为其创建动画后以FBX形式导入，可能会出现材质出现面朝向错误的情况，你可以通过Blender属性面板中的材质选项卡内的视图着色方式，将Alpha钳制改为不透明即可解决此问题，其它格式暂未发现相关问题。
####   ![无标题111](https://user-images.githubusercontent.com/61368414/235972553-517fb5cc-8e17-4512-9000-3cce650f4fad.png)


# Max Caulfield - Whole Body Control System 2nd Edition
## V0.1.2 Second Edition Released on July 23, 2023
This system is based on the bones and shape keys in Blender. It is a full-body control system created for Max Caulfield. It includes Max Caulfield's face and body movements. It is compatible with most full-body motion capture and facial capture software. It is also compatible with Adobe animation libraries. You can directly use FBX format to export and create animation and motion effects for it, and you can also create dynamic effects for it in Blender. The face and body of the Max Caulfield full body control system are separated, so you can only control Max Caulfield's body without affecting his facial movements. Facial movements are controlled by Blender. Shape keys to control its facial expressions, including eyebrows, eyes, nose, mouth, tongue, eyelashes, etc., and set the maximum value of the corresponding shape keys on the face. This branch is only compatible with Blender 3.4-3.6 and above. For the specific version compatibility list, please refer to the instructions below. You can download its 3D software through Blender’s official website, and open and modify its expressions. There are detailed tutorial instructions, which have been described in detail on BiliBili, Youtube, Xigua Video, Douyin and other platforms. You can refer to the relevant information to get how to use It, if you don't know 3D software or Blender, please don't change its related value to avoid problems
    ![Untitled 111](https://user-images.githubusercontent.com/61368414/235973174-15110931-13d0-4702-81d1-53433a60a89d.png)
   
## version compatibility list
<table width="100%" border="1">
   <tbody>
     <tr>
       <td>Version</td>
       <td>Compatible</td>
       <td>Update time</td>
       <td>Model Appearance</td>
       <td>Control system author</td>
     </tr>
     <tr>
       <td>v0.1.1</td>
       <td>Blender 3.4</td>
       <td>May 16, 2023</td>
       <td>Max Caulfield (Butterfly)</td>
       <td>Github：MaxCaulfield（MaxCauIfield）</td>
     </tr>
     <tr>
       <td>v0.1.2</td>
       <td>Blender 3.6</td>
       <td>July 23, 2023</td>
       <td>Max Caulfield (Underwear)</td>
       <td>Github：MaxCaulfield（MaxCauIfield）</td>
     </tr>
     <tr>
       <td>v0.1.1 Remastered</td>
       <td>Blender 3.6</td>
       <td>July 23, 2023</td>
       <td>Max Caulfield (Butterfly)</td>
       <td>Github：MaxCaulfield（MaxCauIfield）</td>
     </tr>
   </tbody>
</table>

# Max Caulfield - Whole Body Control System Version 1
## V0.1.1 Remastered Released on July 23, 2023
### Known issues:
#### - Relevant texture assets were not packaged in the Blend file, this has been fixed
## V0.1.1 First version released on May 3, 2023
### Known issues:
#### - When using facial capture software to create expression animations for Max Caulfield, if his eyebrows are changed, the eyes will appear too large. This problem can be solved by turning off the problem shape key. This problem will be fixed in the next version.
#### ![QQ picture 20230504000055](https://user-images.githubusercontent.com/61368414/235972815-4de50b8c-0b3d-4944-b257-3c34a7b952e8.png)
## V0.1.0 internal beta version released on May 1, 2023, its branch has not yet been announced
### Known issues:
#### - When controlling Max Caulfield's head to rotate (or importing other animation or motion capture software, Max Caulfield's face will be stretched, this problem has been fixed in version V0.1.1.
##### ![QQ picture 20230503235825](https://user-images.githubusercontent.com/61368414/235971809-85d0cd8b-a5d8-4b95-80e9-edf941f7aaee.png)
#### - If you use FBX to import this model, or create an animation for it and then import it in FBX form, the material may face the wrong direction. You can solve this problem by changing the alpha clamp to opaque through the view coloring method in the material tab of the Blender property panel. No related problems have been found in other formats.
#### ![Untitled 111](https://user-images.githubusercontent.com/61368414/235972553-517fb5cc-8e17-4512-9000-3cce650f4fad.png)

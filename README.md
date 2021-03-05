# Object-Oriented Programming Labs

Week 2 - 03/05

1. 再次強調不接受遠距教學，請告訴你遠距的同學退選。
2. 因為修課人數眾多且分兩間教室，為了更好收集大家對課程的問題，每次上課都會有 Zuvio 的問答，回答與否將列入平時成績。
3. 請善用助教時間，本週將會研討延長整題的助教時間。
4. 下周一開始你應該已經完成 tutorial 並且著手開發遊戲。
5. 未符合課程要求的遊戲，將酌量調整成績。
6. Time Log 網站是 https://toggl.com/track/ 使用方法請參照投影片 [Slides](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/3.%20Slides/OOPL_Week_1.pdf)


Week 1 - 02/26

不接受遠距教學，如果你有同學加選但無法到課堂上上課，請他退選。

**請好好閱讀課程需求，選擇的遊戲必須滿足(1)會死掉或闖關失敗(2)要分關卡，評分標準包含遊戲難度與。**

Topic 1: Introducing the course [Slides](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/3.%20Slides/OOPL_Week_1.pdf)

- 學期成績
    - 平時成績 -> 20% 
    - 實習進度展示 -> 20% 
    - 實習報告 -> 30% 
    - 實習成果 -> 30%
- 說明
    - 實習成果之成績未達標準(C+或67 - 69以下)者，不論其他成績為何，其學期成績均調整為不及格。
    - 未完成實習報告所規定之事項者，學期總成績依該規定扣分。
    - 同組兩人貢獻程度不同者，學期成績依貢獻比例適度調整。
- 限制
    - **除非預先通知授課老師請假，則缺席、遲到 1 節課，學期總成績扣 1 分(直接上學校系統)。**
    - You have full control of your grade; thus, do not come to me at the end of semester for asking for grades
- 課程進行
    - 學期中老師(或助教)每隔週(或隔兩週)會考察一次進度，考察的目的是了解遊戲程式的進度，並協助解決程式設計的問題。
    - 平時成績以每次考察時進度之控制為計分標準，進度愈快者成績愈佳。
    - **第二週時需選定遊戲完成分組，並於第二週展示原本遊戲內容與操作方式給老師或助教看([問卷連結](https://forms.gle/rD1nx5tKYaxBARvV8)，否則扣平時成績10分)。**
    - **第三週未完成 Git 練習者，每樣練習扣平時成績 10 分(See Topic 2 below)。**
    - 期末實習報告應指出組員的分工情形以及組員對實習貢獻百分比，以供調整評分之參考。
    - 為量化各組每週投入實習的時間與程式的數量，每次上課時，各組均須上網填寫前一週用於製作遊戲程式的時間與工作內容，並上傳程式。
- Content of this semester
    - 本學期將分組(每組以兩人為限)，製作一個遊戲程式
    - 請根據課程提供的遊戲 framework 進行遊戲開發，不得使用其他 framework
    - 三選一 Windows/Android/HTML5 遊戲程式設計與製作
- Goal of this course
    - Get you familiar with a big project
    - Put the concept of OOP into real use
    - Writing codes as a team

Topic 2: Game [Introduction to Game Framework](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/3.%20Slides/Intro_to_GameFramework.pdf)

- 本遊戲 framework 由[陳偉凱老師](http://www.cc.ntut.edu.tw/~wkchen/)開發，並成為北科資工系大學部重要訓練課程。
- Game is an application framework for developing 2D games
- Game framework was created in 1998 as an object library that provides ready-to-use graphics and sound objects for CSIE OOP lab class.  Over the years, Game has undergone several revisions and evolved into an application framework.
- The Windows version of Game framework is implemented with the Microsoft VC++ based on MFC and DirectX. Starting from 2011, an Android version Game framework is also offered.
- Game framework is released under GPL.
- Game framework provides the following functionalities:
    - A simple and easy-to-use bitmap graphic object and a sound object
    - Built-in state control for game and main control loop with overridable game speed control
    - The selection of the full screen mode and the window mode for presenting the game.
- 進行遊戲開發之前，請閱讀程式碼與[投影片](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/3.%20Slides/Intro_to_GameFramework.pdf)，並完成各平台的 tutorial 再開始寫自己的遊戲。
- We have three diffferent plarforms for games
    - Windows [Source](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/4.%20Source%20Code/game4.10.zip), [Tutorial](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/tree/master/0.%20Documentation)
        - Please download the source code version if you are planning to develop a game under Windows 8/Windows 10.
        - Please follow the following installation instructions to compile and execute the game framework and its sample program.
            1. Install Microsoft Visual Studio 2017 C++
            2. Download and decompress the zip file of source code.
            3. Double click game.sln to open the source code.
        - Compile and execute the sample game. If compilation fails, make sure your Visual Studio and DirectX SDK versions are correct.
        - Follow the tutorials above to add new functionalities or objects to the Game.
        - When your game is fully developed, follow the game deployment instructions above to create setup files for your game.
    - Android [Source](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/4.%20Source%20Code/androidGameV2.4.rar), [Tutorial](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/tree/master/0.%20Documentation)
        - Please download the source code version if you are planning to develop a game under Android
        - Please follow the following installation instructions to compile and execute the game framework and its sample program.
            1. Follow the [Android tutorials](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/0.%20Documentation/Android_tutorials.pdf) to add new functionalities or objects to the Game.
            2. When your game is fully developed, follow the game deployment instructions above to install the game on the phone
    - HTML 5 [Source](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/4.%20Source%20Code/html5_game3.3.zip), [Tutorial](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/tree/master/0.%20Documentation)
        - Please download the file and use a browser to execute the sample game
        - Follow the HTML5 tutorials above to add new functionalities or objects to the Game.
- [Documentation](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/tree/master/0.%20Documentation) can be found on this Gitlab Project

Topic 3: Practice using Git with [SourceTree](https://www.sourcetreeapp.com/)

- 為節省本實驗之硬碟空間，本學期請至 [GitHub](https://github.com/) 註冊帳號
- 在你平時會開發的電腦上設定，別在電腦教室設定，他每次都會不見
- 兩人一組(分別稱為某甲與某乙)
    - 某甲 練習[一](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/1.%20Practice%20Git/GitTutorial-1.pdf)、練習[二](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/1.%20Practice%20Git/GitTutorial-2.pdf)
    - 某乙 練習[一](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/1.%20Practice%20Git/GitTutorial-1.pdf)
    - 某甲 練習[三](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/1.%20Practice%20Git/GitTutorial-3.pdf)、練習[四](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/1.%20Practice%20Git/GitTutorial-4.pdf)
    - 某乙 練習[三](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/1.%20Practice%20Git/GitTutorial-3.pdf)、練習[五](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/1.%20Practice%20Git/GitTutorial-5.pdf)
    - 某甲 練習[六](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/1.%20Practice%20Git/GitTutorial-6.pdf)、練習[七-甲](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/1.%20Practice%20Git/GitTutorial-7A.pdf)
    - 某乙 練習[七-乙](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/1.%20Practice%20Git/GitTutorial-7B.pdf)
    - 某甲 練習[八-甲](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/1.%20Practice%20Git/GitTutorial-8A.pdf)
    - 某乙 練習[八-乙](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/1.%20Practice%20Git/GitTutorial-8B.pdf)
- 一人一組(稱為某甲)
    - 練習[一](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/1.%20Practice%20Git/GitTutorial-1.pdf)、[二](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/1.%20Practice%20Git/GitTutorial-2.pdf)、[三](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/1.%20Practice%20Git/GitTutorial-3.pdf)、[五](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/1.%20Practice%20Git/GitTutorial-5.pdf)、[六](https://css-gitlab.csie.ntut.edu.tw/109000000/oopl2020s/-/blob/master/1.%20Practice%20Git/GitTutorial-6.pdf)
- 第三週未完成練習者，每樣練習扣平時成績 10 分。(before 2021/3/12)
- 請於第三週上課時間，將練習成果展現給老師或是助教檢查。(on 2021/3/12)




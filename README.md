# Collocation-Searcher
This is a regex based collocation searcher V0.0.0, by Leo Lei and Rex Gao.
Thanks for Pan Yang and Tian Haiyan.
根据雷蕾老师周二的搭配检索方法的分享，用了一个小时写成了这个软件，可以根据正则表达式查询相关词语的搭配，支持所有语言的文本，对学术英语写作的帮助很大。
目前比较粗糙，之后会尝试根据大家反馈的问题进行更新。
感谢雷老师，杨攀大哥和田海燕同学，这三位对我意义重大，感谢父母，感谢朋友，感谢各位师兄师姐，也感谢所有支持我的人！

### 示例：（来自雷蕾老师）
1. regex: "\w+ corroborate"
2. top: 20
选择前20个高频的搭配。

### 值得思考的学术英语搭配问题:（来自雷蕾老师）
1. adv + corroborate
2. mitigate + n
3. v + the magnitude
4. p-value lower than or p-value less than
5. more favorable impact?

## Patch Notes V0.0.1：
1. Fix an issue that is likely to fall in the loop of selecting the corpus folder.
2. Re-adjust the Font and Entry size of the Regex Section to make it more comfortable.
3. Add quick search function to reduce the time cost in searching within 6 seconds.
4. Adjust the program size to protect eyesight of users.
5. Fix bugs that likely make the program crash.

## Patch Notes V1.0.0:
Note that this is the ultimate edition of collocation searcher by Leo Lei and Rex Gao.
It means that the update may not happen in the future unless there are some fatal bugs.
1. Fix some coordination problem. User can now adjust the size of the program freely, without the change of the inner structure.
2. Add right click menu for the output block. Copy&save option is recommended if you encounter some amazing expressions.
3. Some minor bug fixes and the icon adjustment. Keep caution that the program need that ".ico" file to execute. Make sure to download them as a whole.
4. Avoid the appearance of background console, which is quite annoying.

## Cleansing.exe is provided. Run cleansing.exe and clean the corpus files first. Then run the collocation searcher to obtain the best performance.
Hope for the best!
Leo Lei & Rex Gao
2019.11.9
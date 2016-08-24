# TestEditTextInputType
edittext
在开发的过程中，通常会用到EditText，如何让虚拟键盘来适应输入框中内容的类型，通常我们都会在xml文件中加入android:inputType=""。

android:inputType="none"android:inputType="text"android:inputType="textCapCharacters"//前3个输入普通字符android:inputType="textCapWords"//单词首字母大小

android:inputType="textCapSentences"//仅第一个字母大小

android:inputType="textAutoCorrect"android:inputType="textAutoComplete"//前两个自动完成

android:inputType="textMultiLine"//多行输入

android:inputType="textImeMultiLine"//输入法多行（不一定支持）

android:inputType="textNoSuggestions"//不提示

android:inputType="textUri"//URI格式

android:inputType="textEmailAddress"//电子邮件地址格式

android:inputType="textEmailSubject"//邮件主题格式

android:inputType="textShortMessage"//短消息格式

android:inputType="textLongMessage"android:inputType="textPersonName"//人名格式

android:inputType="textPostalAddress"//邮政格式

android:inputType="textPassword"//密码格式

android:inputType="textVisiblePassword"//密码可见格式

android:inputType="textWebEditText"//作为网页表单的文本格式

android:inputType="textFilter"//文本筛选格式

android:inputType="textPhonetic"//拼音输入格式

android:inputType="number"//数字格式

android:inputType="numberSigned"//有符号数字格式

android:inputType="numberDecimal"//可以带小数点的浮点格式

android:inputType="phone"//拨号键盘

android:inputType="datetime"android:inputType="date"//日期键盘

android:inputType="time"//时间键盘

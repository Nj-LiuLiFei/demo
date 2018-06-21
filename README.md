# demo
gitHub的初步使用
# 表格使用
<table>
  <thead>
    <tr>
      <th align="left">方法名</th>
      <th align="center">返回值类型</th>
      <th align="left">作用</th>
      <th align="left">备注</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left">isEmpty(Object str)</td>
      <td align="center">boolean</td>
      <td align="left">判断字符串是否为Null或者空字符串</td>
      <td align="left"><code>null</code>和<code>''</code>都为true</td>
    </tr>
    <tr>
      <td align="left">hasLength(CharSequence str)</td>
      <td align="center">boolean</td>
      <td align="left">判断字符串长度是否大于1</td>
      <td align="left"><code>null</code>和<code>''</code>都为false</td>
    </tr>
  </tbody>
</table>

### 多行文本框
    这是一个有多行的文本框
    你可以写入代码等,每行文字只要输入两个Tab再输入文字即可
    这里你可以输入一段代码
    
    
### 比如我们可以在多行文本框里输入一段代码,来一个Java版本的HelloWorld吧  
    public class HelloWorld {  
  
      /**  
      * @param args  
      */  
    public static void main(String[] args) {  
      System.out.println("HelloWorld!");  

      }  
  
    }  

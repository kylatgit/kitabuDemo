## kitabu demo

### Demo for Notes by kitabu

#### Title

<table>
	<tr>
		<td>##</td>
		<td>Chapter title</td>
	</tr>
	<tr>
		<td>###</td>
		<td>Section title</td>
	</tr>
	<tr>
		<td>####</td>
		<td>Item title</td>
	</tr>
</table>

#### Itemize

`* item`

or

`* item`<br>
&nbsp;&nbsp;&nbsp;&nbsp;`* subitem`

#### Hyperlink

`[linkname](linkaddress)`

#### Command Line Effect

paragraph<br>
&nbsp;&nbsp;&nbsp;&nbsp;`command`<br>
paragraph<br>

#### Quote Content

`<p class="notice">content</p>`

#### Put Images

`<p class="figure"><img src="../images/file" alt="name"></p>`
<p class="figure"><img src="../images/test.png" alt="name"></p>

ps: 圖片放在images/.

<br><br>

#### Table

<table>
	<thead>
		<tr>
			<th>head-left</th>
			<th>head-right</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>1,1</td>
			<td>1,2</td>
		</tr>
		<tr>
			<td>2,1</td>
			<td>2,2</td>
		</tr>
	</tbody>
</table>

ps: `table>thead+tbody` then `tr>th*2` and `tr*2>td*2`.

#### Code Highlight

@ @ @ java main.java @ @ @

@@@ java

package pkPackageName;

public class main{
	public static void main(String[] args){
		System.out.println("Hello, world!");
	}
}

@@@

ps: 原始碼放在code/, 不用加路徑!

#### 其餘

`&nbsp;`<br>

`<br>`
Moonshine
=========

**Moonshine** is a dark color-scheme for IntelliJ IDEA 12.x based on "Dracula", just less bloody.

Status
------
This table lists the languages (and other sections under `Preferences | Editor | Colors & Fonts`)
for which the syntax highlighting has been adapted:
<table>
  <tr>
		<th>Language/Section</th>
		<th>Supported</th>
	</tr>
	<tr>
		<td>General</td>
		<td align="center"><b>Yes</b></td>
	</tr>
  <tr>
		<td>Console</td>
		<td align="center"><b>Yes</b></td>
	</tr>
	<tr>
		<td>Java</td>
		<td align="center"><b>Yes</b></td>
	</tr>
  <tr>
    <td>Android Logcat</td>
		<td align="center"><b>Yes</b></td>
  </tr>
  <tr>
		<td>Diff</td>
		<td align="center"><b>Yes</b></td>
	</tr>
  <tr>
		<td>File Status</td>
		<td align="center"><b>Yes</b></td>
	</tr>
</table>

Installation
------------
### Option 1: Install using "Import Settings..."

1. Go to `File | Import Settings...` and specify the `moonshine` directory. Clik `OK` in the dialog that appears.
2. Restart IntelliJ IDEA
3. Go to `Preferences | Editor | Colors & Fonts` and select one of the new color themes.

### Option 2: Manual installation

1. Copy the `Moonshine.xml` file into your IntelliJ IDEA preferences color directory. It is typically in:  
  - Mac OS X:
      `~/Library/Preferences/IntelliJIdea12/colors`
  - Windows:
      `Documents and Settings/<user>/.IntelliJIdea12/config/colors`
2. Restart IntelliJ IDEA
3. Go to `Preferences | Editor | Colors & Fonts` and select one of the new color themes.

Notes
-----
This theme revolves around languages I work with on a daily basis. If you are using some of the more esoteric languages supported by IDEA, you may not have proper highlighting in their respective files. Also, a font in a theme may or may not be available on your platform in which case IDEA will default to something else; typically, any monospace font is an acceptable replacement.
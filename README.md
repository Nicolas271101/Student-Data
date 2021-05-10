# Student-Data
#This is how to create a form data using html

<!DOCTYPE html>
<html>
	<head>
		<title>How to create a form</title>
	</head>
	<body>
		<fieldset>
			<h1 align="center"><font face="arial">STUDENT DATA</font></h1>
			<table border="0" align="center" cellspacing="2" cellpadding="">
				<tr>
					<th rowspan="7" bgcolor="green" width="14" align="left"><font face="arial">PERSONAL DATA</font></th>
					<td><font face="arial">Name</font></td>
					<td><input type="text" name="name" id="fName"></td>
					<td><input type="text" name="name" id="mName"></td>
					<td><input type="text" name="name" id="lName"></td>
				</tr>
				<tr>
					<td></td>
					<td><label for="fName"><font face="arial">First Name</font></label></td>
					<td><label for="mName"><font face="arial">Middle Name</font></label></td>
					<td><label for="lName"><font face="arial">Last Name</font></label></td>
				</tr>
				<tr>
					<td><font face="arial">NIM</font></td>
					<td colspan="2"><input type="text" name="NIM" size="50"></td>
					<td>
						<select id="Year" name="Year">
							<option value="1">--Year of University Entrance--</option>
							<option value="2">2014</option>
							<option value="3">2015</option>
							<option value="4">2016</option>
							<option value="5">2017</option>
							<option value="6">2018</option>
							<option value="7">2019</option>
							<option value="8">2020</option>
						</select>
					</td>
				</tr>
				<tr>
					<td><font face="arial">Faculty, Department & Program</font></td>
					<td>
						<select id="Faculty" name="Faculty">
							<option value="1">--Faculty--</option>
							<option value="2">Engineering</option>
							<option value="3">Law</option>
							<option value="4">Economics</option>
						</select>
					</td>
					<td>
						<select id="Department" name="Department">
							<option value="1">--Department--</option>
							<option value="2">Informatics</option>
							<option value="3">Industrial Engineering</option>
							<option value="4">Electrical Engineering</option>
						</select>
					</td>
					<td>
						<select id="Program" name="Program">
							<option value="1">--Study Program--</option>
							<option value="2">Informatics</option>
							<option value="3">Infomation System</option>
							<option value="4">Industrial Engineering</option>
							<option value="5">Mechanical Engineering</option>
							<option value="6">Mechatronics Engineering</option>
							<option value="7">Electrical Engineering</option>
						</select>
					</td>
				</tr>
				<tr>
					<td><font face="arial">Gender</font></td>
					<td>
						<label for="male"><font face="arial">Male</font></label>
						<input name="gender" id="male" type="radio">
						<label for="female"><font face="arial">Female</font></label>
						<input name="gender" id="female" type="radio">
					</td>
				</tr>
				<tr>
                    <td>
                        <font face="arial">Email</font>
                    </td>
                    <td colspan="3"><input type="text" name="Email" size="80"></td>
                </tr>
                <tr>
                    <td valign="top">
                        <font face="arial">Address</font>
                    </td>
                    <td colspan="3"><textarea name="address" cols="82" rows="3"></textarea></td>
                </tr>
                <tr>
                    <td height="30"></td>
                </tr>
                <tr>
                    <th rowspan="7" bgcolor="green" align="left">
                        <font face="arial">SUPPORT AND ACCOUNT</font>
                    </th>
                    <td colspan="4">
                        <font face="arial">Do you have scholarship support?</font>
                    </td>
                </tr>
                <tr>
                    <td>
                        <input type="radio" name="support" id="s_no">
                        <label for="s_no">
                            <font face="arial">No</font>
                        </label>
                    </td>
                </tr>
                <tr>
                    <td>
                        <input type="radio" name="support" id="s_yes">
                        <label for="s_yes">
                            <font face="arial">Yes</font>
                        </label>
                    </td>
                    <td colspan="3">
                        <input type="text" size="80">
                    </td>
                </tr>
                <tr>
                    <td></td>
                </tr>
                <tr>
                    <td colspan="4">
                        <font face="arial">Do you have access to the trunojoyo emal account?</font>
                    </td>
                </tr>
                <tr>
                    <td>
                        <input type="radio" name="access" id="a_no">
                        <label for="a_no">
                            <font face="arial">No</font>
                        </label>
                    </td>
                </tr>
                <tr>
                    <td>
                        <input type="radio" name="access" id="a_yes">
                        <label for="a_yes">
                            <font face="arial">Yes</font>
                        </label>
                    </td>
                </tr>
                <tr>
                    <td height="20"></td>
                </tr>
                <tr>
                    <th rowspan="6" bgcolor="green" align="left">
                        <font face="arial">EDUCATION</font>
                    </th>
                    <td>
                        <font face="arial">Primary School</font>
                    </td>
                    <td><input type="text" id="p_school"></td>
                    <td><input type="text" id="p_url"></td>
                    <td><select name="p_year" id="p_year">
                            <option value="1">--Year of Graduate--</option>
                            <option value="2">2008</option>
                            <option value="3">2009</option>
                            <option value="4">2010</option>
                            <option value="5">2011</option>
                            <option value="6">2012</option>
                            <option value="7">2013</option>
                            <option value="8">2014</option>
                        </select></td>
                </tr>
                <tr>
                    <td></td>
                    <td><label for="p_school">
                            <font face="arial" size="2">School Name</font>
                        </label></td>
                    <td><label for="p_url">
                            <font face="arial" size="2">Website URL</font>
                        </label></td>
                </tr>
                <tr>
                    <td>
                        <font face="helvetica">Middle School</font>
                    </td>
                    <td><input type="text" id="m_school"></td>
                    <td><input type="text" id="m_url"></td>
                    <td><select name="m_year" id="m_year">
                            <option value="1">--Year of Graduate--</option>
                            <option value="2">2011</option>
                            <option value="3">2012</option>
                            <option value="4">2013</option>
                            <option value="5">2014</option>
                            <option value="6">2015</option>
                            <option value="7">2016</option>
                            <option value="8">2017</option>
                        </select></td>
                </tr>
                <tr>
                    <td></td>
                    <td><label for="m_school">
                            <font face="arial" size="2">School Name</font>
                        </label></td>
                    <td><label for="m_url">
                            <font face="arial" size="2">Website URL</font>
                        </label></td>
                </tr>
                <tr>
                    <td>
                        <font face="arial">High School</font>
                    </td>
                    <td><input type="text" id="h_school"></td>
                    <td><input type="text" id="h_url"></td>
                    <td><select name="h_year" id="h_year">
                            <option value="1">--Year of Graduate--</option>
                            <option value="2">2014</option>
                            <option value="3">2015</option>
                            <option value="4">2016</option>
                            <option value="5">2017</option>
                            <option value="6">2018</option>
                            <option value="7">2019</option>
                            <option value="8">2020</option>
                        </select></td>
                </tr>
                <tr>
                    <td></td>
                    <td><label for="h_school">
                            <font face="arial" size="2">School Name</font>
                        </label></td>
                    <td><label for="h_url">
                            <font face="arial" size="2">Website URL</font>
                        </label></td>
                </tr>
                <tr>
                    <td height="30"></td>
                </tr>
                <tr>
                    <th rowspan="5" bgcolor="green" align="left">
                        <font face="arial">SOFTWARE SKILL</font>
                    </th>
                    <td>
                        <font face="arial">Office Software</font>
                    </td>
                    <td>
                        <input type="checkbox" name="software" id="m_word">
                        <label for="m_word">
                            <font face="arial">Microsoft Word</font>
                        </label>
                        <br>
                        <input type="checkbox" name="software" id="m_excel">
                        <label for="m_excel">
                            <font face="arial">Microsoft Excel</font>
                        </label>
                    </td>
                    <td>
                        <input type="checkbox" name="software" id="m_access">
                        <label for="m_access">
                            <font face="arial">Microsoft Access</font>
                        </label>
                        <br>
                        <input type="checkbox" name="software" id="other_software">
                        <label for="other_software">
                            <font face="arial">Other</font>
                        </label>
                    </td>
                </tr>
                <tr>
                    <td height="20"></td>
                </tr>
                <tr>
                    <td>
                        <font face="arial">Operating System</font>
                    </td>
                    <td>
                        <input type="checkbox" name="system" id="windows">
                        <label for="windows">
                            <font face="arial">Windows</font>
                        </label>
                        <br>
                        <input type="checkbox" name="system" id="linux">
                        <label for="linux">
                            <font face="arial">Linux</font>
                        </label>
                    </td>
                    <td>
                        <input type="checkbox" name="system" id="macos">
                        <label for="macos">
                            <font face="arial">macOS</font>
                        </label>
                        <br>
                        <input type="checkbox" name="system" id="other_sytem">
                        <label for="other_sytem">
                            <font face="arial">Other</font>
                        </label>
                    </td>
                </tr>
                <tr>
                    <td height="20"></td>
                </tr>
                <tr>
                    <td>
                        <font face="arial">Programing Language</font>
                    </td>
                    <td>
                        <input type="checkbox" name="language" id="python">
                        <label for="python">
                            <font face="arial">Python</font>
                        </label>
                        <br>
                        <input type="checkbox" name="language" id="java">
                        <label for="java">
                            <font face="arial">Java</font>
                        </label>
                    </td>
                    <td>
                        <input type="checkbox" name="language" id="c_plus">
                        <label for="c_plus">
                            <font face="arial">C++</font>
                        </label>
                        <br>
                        <input type="checkbox" name="language" id="other_language">
                        <label for="other_language">
                            <font face="arial">Other</font>
                        </label>
                    </td>
                </tr>
                <tr>
                    <td height="30"></td>
                </tr>
                <tr>
                    <td colspan="5" align="center">
                        <input type="submit" value="Submit Form">
                    </td>
                </tr>
			</table>
		</fieldset>
	</body>
</html>

<html>
<head>
	<meta charset="utf-8" />
	<title>회원가입</title>
</head>
<body>
	<form method="post" action="signup.jsp" id="signupform" name="signupform">
		<h1>회원가입</h1>
			<fieldset>
				<legend>입력사항</legend>
					<table>
						<tr>
							<td>닉네임</td>
							<td><input id="username" type="text" size="35" name="username" placeholder="닉네임"></td>
						</tr>
						<tr>
							<td>아이디</td>
							<td><input id="userid" type="text" size="35" name="userid" placeholder="아이디"></td>
						</tr>
						<tr>
							<td>비밀번호</td>
							<td><input id="userpw" type="password" size="35" name="userpw" placeholder="비밀번호"></td>
						</tr>

					</table>

				<input type="submit" value="가입하기" action="signup.jsp"/><input type="reset" value="다시쓰기" />
			
		</fieldset>
	</form>
</body>
</html>

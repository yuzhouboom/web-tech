<template>
    <form name = logon method = post>
<table>
<td colspan = 2>Login</td>
</tr>
<tr>
<td>Username：</td>
<td><input type = text name = user size = 16/></td>
</tr>
<tr>
<td>Password：</td>
<td><input type = password name = password size = 16/></td>
</tr>
<tr>
<td><input type = submit value = submit></td>
</tr>
</table>
</form> 


</template>

<script>
export default {
    name: 'Login',
}
</script>


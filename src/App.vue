<script setup>

</script>

<template>
    
    <center><h1>Crystal Games </h1></center>
    <center><img src="https://o.remove.bg/downloads/6eb1c096-cece-4119-95fb-5e2cdce19653/p-removebg-preview.png" alt="Logo Gemes" style="width:322px;height:330px;" /> </center>
    <h2><center>Login Crystal</center></h2>
    <form action="/action_page.php"> <center>
        <label for="usname">Username:</label>
        <input type="text" id="usname" name="usname"><br><br>
        <label for="password">Pasworrd:</label>
        <input type="text" id="Password" name="Password"><br><br>
        <input type="submit" value="Submit">
        <p>Sign In</p>
        <p><a href="https://www.google.com/">Google</a></p></center>
    </form>

    <h3>Nama Game & Harga:</h3>
    <table style="width:50%">
        <tr>
            <th>Nama Game</th>
            <th>Harga</th>
        </tr>
        <tr>
            <td>GTA V</td>
            <td>300k</td>
        </tr>
        <tr>
            <td>FIFA</td>
            <td>759k</td>
        </tr>
        <tr>
            <td>Man Eater</td>
            <td>216k</td>
        </tr>
        <tr>
            <td>Dead By Daylight</td>
            <td>135k</td>
        </tr>
        <tr>
            <td>Tomb Raider</td>
            <td>570k</td>
        </tr>
    </table>
    <form action="/action_page.php">
        <label for="install">Install Game:</label>
        <select name="install" id="install">
            <option value="GTA V">GTA V</option>
            <option value="FIFA">FIFA</option>
            <option value="Man Eater">Man Eater</option>
            <option value="Dead By Daylight">Dead By Daylight</option>
            <option value="Tomb Raider">Tomb Raider</option>
        </select>
        <br><br>
        <input type="Install" value="Install">
    </form>

    <h4>Komentar</h4>
    <form action="/action_page.php">
        <p><label for="Crystal Gemes">Review Game:</label></p>
        <textarea id="Crystal Gemes" name="Crystal Gemes" rows="4" cols="50">Kritik Dan Saran</textarea>
        <br>
        <input type="submit" value="Submit">
    </form>
    
    <h5>copyright</h5>
    <h6>Created by: Muhammad Khalil Gibran</h6>


</template>

<style scoped>

</style>

<style>
h6,h5 {text-align: center;}
form {margin-top: 1%;}
 body { background-image: url("https://img.freepik.com/free-vector/white-abstract-background-design_23-2148825582.jpg?w=1060&t=st=1680104524~exp=1680105124~hmac=3e658578c23f86f4a06488a2b32e720ff67c377ce2b813fc4dc47e18cf436e2b");
 background-size: cover;}
 table, th, td {border:2px solid black;}
 
</style>

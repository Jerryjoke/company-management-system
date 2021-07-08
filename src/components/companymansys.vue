<template>
  <div>
    <h1>company details</h1>
    <div class="container">
      <table>
        <tr>
          <td>company name</td>
          <td><input type="text" name="name" id="name" /></td>
        </tr>
        <tr>
          <td>Nature of business</td>
          <td><input type="text" name="Fname" id="Fname" /></td>
        </tr>

        <tr>
          <td></td>
          <td><input type="button" value="save" /></td>
        </tr>
      </table>
    </div>
    <h1>Branch details</h1>
    <div class="container">
      <table>
        <tr>
          <td>Company name:</td>
          <td>
            <select name="companysl" id="companysl">
              <option value="-1">select</option>
              <option value="">Company</option>
            </select>
          </td>
        </tr>
        <tr>
          <td>Branch name</td>
          <td><input type="text" name="Fname" id="Fname" /></td>
        </tr>
        <tr>
          <td>GSD No.</td>
          <td><input type="text" name="Fname" id="Fname" /></td>
        </tr>
        <tr>
          <td>Address</td>
          <td><input type="address" name="Fname" id="Fname" /></td>
        </tr>
        <tr>
          <td></td>
          <td><input type="button" value="search" /></td>
        </tr>
      </table>
    </div>

    <div class="container">
      <table border="2">
        <h4><u>Company name</u></h4>
        <tr>
          <th>Branch name</th>
          <th>GSD No.</th>
          <th>Address</th>
        </tr>
        <tr>
          <td>company</td>
          <td>gcd</td>
          <td>address</td>
        </tr>
      </table>
    </div>
  </div>
</template>
<script>
export default {
  name: "companymansys",
};
</script>
<style lang="stylus" scoped>
.container {
  width: 400px;
  margin: auto;
  height: auto;
  padding: 15px;
  border: 1px solid black;
}

td {
  width: 100%;
  margin: auto;
  padding: 10px;
  font-size: 20px;
  font-weight: bold;
}

h4 {
  float: left;
}

#companysl {
  width: 100%;
  height: 25px;
}

input[type = button] {
  font-size: 20px;
  border-radius: 5px;
}
</style>
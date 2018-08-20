<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ul>
      <li>
        <h3>Pages Secure <br><span>(b_app)</span></h3>
        <table>
          <tr>
            <td>Project name:</td>
            <td>b_app</td>
          </tr>
          <tr>
            <td>Backend:</td>
            <td>ZF 2</td>
          </tr>
          <tr>
            <td>Frontend:</td>
            <td>HTML, JS, CSS, </td>
          </tr>
          <tr>
            <td>Dependences:</td>
            <td>zend_blib</td>
          </tr>
        </table>
      </li>
      <li>
        <h3>Chk V2 <br><span>(zend_chk)</span></h3>
        <table>
          <tr>
            <td>Project name:</td>
            <td>zend_chk</td>
          </tr>
          <tr>
            <td>Backend:</td>
            <td>ZF 2</td>
          </tr>
          <tr>
            <td>Frontend:</td>
            <td>HTML, JS, CSS</td>
          </tr>
          <tr>
            <td>Dependences:</td>
            <td>zend_blib</td>
          </tr>
        </table>
      </li>
      <li>
        <h3>MP <br><span>(b_pt)</span></h3>
        <table>
          <tr>
            <td>Project name:</td>
            <td>b_pt</td>
          </tr>
          <tr>
            <td>Backend:</td>
            <td>PHP legacy</td>
          </tr>
          <tr>
            <td>Frontend:</td>
            <td>HTML, JS, CSS, VueJS 2,  </td>
          </tr>
          <tr>
            <td>Dependences:</td>
            <td>blib</td>
          </tr>
        </table>
      </li>
      <li>
        <h3>OP <br><span>(b_ct)</span></h3>
        <table>
          <tr>
            <td>Project name:</td>
            <td>b_ct</td>
          </tr>
          <tr>
            <td>Backend:</td>
            <td>PHP legacy</td>
          </tr>
          <tr>
            <td>Frontend:</td>
            <td>HTML, JS, CSS, VueJS 2 </td>
          </tr>
          <tr>
            <td>Dependences:</td>
            <td>blib</td>
          </tr>
        </table>
      </li>
      <li>
        <h3>TP <br><span>(b_tools)</span></h3>
        <table>
          <tr>
            <td>Project name:</td>
            <td>b_tools</td>
          </tr>
          <tr>
            <td>Backend:</td>
            <td>PHP legacy</td>
          </tr>
          <tr>
            <td>Frontend:</td>
            <td>HTML, JS, CSS, VueJS 2 </td>
          </tr>
          <tr>
            <td>Dependences:</td>
            <td>blib</td>
          </tr>
        </table>
      </li>
      <li>
        <h3>TzP <br><span>(b_tz)</span></h3>
        <table>
          <tr>
            <td>Project name:</td>
            <td>b_tz</td>
          </tr>
          <tr>
            <td>Backend:</td>
            <td>PHP legacy</td>
          </tr>
          <tr>
            <td>Frontend:</td>
            <td>HTML, JS, CSS, VueJS 2 </td>
          </tr>
          <tr>
            <td>Dependences:</td>
            <td>zend_blib</td>
          </tr>
        </table>
      </li>
    </ul>
  </div>
</template>

<script>

export default {
  name: 'hello',
  data() {
    return {
      msg: 'Information projects',
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
  background-color: #f1f1f1;
}

a {
  color: #35495E;
}
td, h3 > span {
  font-size: 12px;
}
</style>

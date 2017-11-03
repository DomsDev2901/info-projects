<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ul>
      <li>
        <h3>Pages Secure <br><span>(bongo_app)</span></h3>
        <table>
          <tr>
            <td>Project name:</td>
            <td>bongo_app</td>
          </tr>
          <tr>
            <td>Backend:</td>
            <td>Zendframework 2</td>
          </tr>
          <tr>
            <td>Frontend:</td>
            <td>HTML, JS, CSS, </td>
          </tr>
          <tr>
            <td>Dependences:</td>
            <td>zend_bongolib</td>
          </tr>
        </table>
      </li>
      <li>
        <h3>Checkout V2 <br><span>(zend_checkout)</span></h3>
        <table>
          <tr>
            <td>Project name:</td>
            <td>zend_checkout</td>
          </tr>
          <tr>
            <td>Backend:</td>
            <td>Zendframework 2</td>
          </tr>
          <tr>
            <td>Frontend:</td>
            <td>HTML, JS, CSS</td>
          </tr>
          <tr>
            <td>Dependences:</td>
            <td>zend_bongolib</td>
          </tr>
        </table>
      </li>
      <li>
        <h3>Merchant Portal <br><span>(bongo_partnertools)</span></h3>
        <table>
          <tr>
            <td>Project name:</td>
            <td>bongo_partnertools</td>
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
            <td>bongolib</td>
          </tr>
        </table>
      </li>
      <li>
        <h3>Order Portal <br><span>(bongo_customertools)</span></h3>
        <table>
          <tr>
            <td>Project name:</td>
            <td>bongo_customertools</td>
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
            <td>bongolib</td>
          </tr>
        </table>
      </li>
      <li>
        <h3>Tools Portal <br><span>(bongo_tools)</span></h3>
        <table>
          <tr>
            <td>Project name:</td>
            <td>bongo_tools</td>
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
            <td>bongolib</td>
          </tr>
        </table>
      </li>
      <li>
        <h3>Toolz Portal <br><span>(bongo_toolz)</span></h3>
        <table>
          <tr>
            <td>Project name:</td>
            <td>bongo_toolz</td>
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
            <td>zend_bongolib</td>
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

<script>
  const people = [
    { id: 1, name: "Maksim" },
    { id: 2, name: "Elena" },
  ];
</script>

<!-- !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!! -->

<!-- <script>
  import Person from "./Person.svelte";

  const people = [
    { id: 1, name: "Maxim", age: 24, job: "Frontend" },
    { id: 2, name: "Elena", age: 17, job: "Student" },
  ];

  let name = "Igor";
  let age = 20;
  let jobTitle = "Backend";
</>

<h1>Application</h1>
<Person name={people[0].name} age={people[0].age} job={people[0].job} />
<Person {...people[1]} />
<Person {name} {age} job={jobTitle} />
<style>
</> -->

<!-- !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!! -->

<!-- <script>
  //   import Main from "./Main.svelte";

  let value = "Hello";
  $: error = !isValid(value);

  function isValid(val) {
    return val.length > 5 && val.length < 10;
  }
</script>

<h1>Application {value}</h1>

<input type="text" bind:value class:red={error} class:green={!error} />
{#if value.length < 5}
  <p>Длина меньше 5 символов</p>
{:else if value.length > 10}
  <p>Длина больше 10 символов</p>
{:else}
  <p>Длина между 5 и 10 символов</p>
{/if}

<style>
  input {
    outline: none;
  }

  .red {
    border-color: red;
  }
  .green {
    border-color: green;
  }
</style> -->

<style>
</style>

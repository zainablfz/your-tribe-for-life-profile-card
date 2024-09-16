<script>
  export let data;
</script>

<svg
  xmlns="http://www.w3.org/2000/svg"
  width="48"
  height="48"
  viewBox="0 0 48 48"
  fill="none"
>
  <path
    d="M30 36L18 24L30 12"
    stroke="#E3B6B6"
    stroke-width="4"
    stroke-linecap="round"
    stroke-linejoin="round"
  />
</svg>

<h1>{data.person.name}</h1>
<p>Squad 2D</p>
<button> Update</button>

<svg
  xmlns="http://www.w3.org/2000/svg"
  width="35"
  height="34"
  viewBox="0 0 35 34"
  fill="none"
>
  <path
    d="M5.83334 17V28.3333C5.83334 29.0848 6.14063 29.8055 6.68762 30.3368C7.2346 30.8682 7.97646 31.1667 8.75001 31.1667H26.25C27.0236 31.1667 27.7654 30.8682 28.3124 30.3368C28.8594 29.8055 29.1667 29.0848 29.1667 28.3333V17M23.3333 8.50001L17.5 2.83334M17.5 2.83334L11.6667 8.50001M17.5 2.83334V21.25"
    stroke="#E3B6B6"
    stroke-width="4"
    stroke-linecap="round"
    stroke-linejoin="round"
  />
</svg>

<ul>
  <li>Github</li>
  <li>Linkedin</li>
  <li>E-mail</li>
  <li>Codepen</li>
</ul>

<h2>What's New</h2>
<p>Version 2.3</p>
<p>{data.person.bio}</p>

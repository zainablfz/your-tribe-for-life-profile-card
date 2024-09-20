<script>
  export let data;
</script>

<main>
  <article>
    <svg
      xmlns="http://www.w3.org/2000/svg"
      width="48"
      height="44"
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
    <div class="container">
      <img src="/memoji.jpeg" alt="memoji zainab" width="100" height="100" />
      <div class="text-container">
        <h1>{data.person.name}</h1>
        <p>Squad 2D</p>
      </div>
    </div>
    <div class="action-container">
      <button>Update</button>

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
    </div>
    <ul>
      <li>Github</li>
      <li>Linkedin</li>
      <li>E-mail</li>
      <li>Codepen</li>
    </ul>
    <div class="text-box">
      <h2>What's New</h2>
      <p>Version 2.3</p>
      <p class="bio">{data.person.bio}</p>
    </div>
  </article>
</main>

<style>
  article {
    background-color: var(--background-card);
    margin: 1em;
    padding: 1em;
    width: 400px;
    height: 450px;
    border-radius: 10px;
  }

  .container {
    display: flex;
    align-items: flex-start;
  }

  .text-container {
    padding-left: 1em;
    padding-top: 1em;
  }
  img {
    border-radius: 50%;
  }

  .action-container {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    padding-left: 2.8em;
  }

  button {
    display: flex;
    justify-content: center;
    padding: 0.8em;
    margin-top: em;
    width: 6em;
    border-radius: 10px;
    background-color: var(--accent-color);
    border: none;
    font-weight: bold;
    color: white;
  }

  ul {
    padding: 0.2em;
    margin: 1em;
    display: flex;
    justify-content: center;
    gap: 0;
    border: 1px solid black;
    text-align: center;
  }

  li {
    border-right: 1px solid black;
    padding-right: 1em;
    padding-left: 1em;
    text-decoration: underline;
    cursor: pointer;
  }

  li:last-child {
    border-right: none;
    padding-right: 0;
  }

  .text-box {
    padding-top: 1em;
  }

  .bio {
    padding-top: 1em;
    padding-bottom: 1em;
  }
</style>

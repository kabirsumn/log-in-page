<template>
  <form action="post" id="form">
    <h3>Get start</h3>
    <label for="username">
      <p>User Name</p>
      <input
        type="text"
        name="username"
        id="username"
        placeholder="username"
        required
      />
    </label>
    <label for="password">
      <p>Password</p>
      <input
        type="password"
        name="password"
        id="password"
        placeholder="password"
        required
      />
    </label>

    <button class="btn" type="submit">Log in</button>
  </form>
</template>

<script>
export default {};
</script>

<style>
#form {
  color: #666;
  width: 400px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 1rem;
  padding: 0 1rem 1.75rem;
  border: 1px solid #d1bfbf;
  border-radius: 5px;
  box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px,
    rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px,
    rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
}
label {
  width: 100%;
}
#form input {
  color: #4e3b3b;
  width: 100%;
  height: 40px;
  padding: 0 30px 0 5px;
  border: 2px solid #c4c4c4;
  border-radius: 8px;
  outline: none;
  font-size: 1.25em;
}

.btn {
  background-color: #45e989;
  color: #444;
  font-size: 1.4em;
  margin-left: auto;
  padding: 0.5rem 0.75rem;
  border: none;
  border-radius: 6px;
  outline: none;
  cursor: pointer;
}
</style>

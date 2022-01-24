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
  </form>
</template>

<script>
export default {};
</script>

<style>
#form {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 1rem;
}
</style>

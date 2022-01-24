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
  width: 400px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 1rem;
  padding: 0 1rem 1.75rem;
  border: 1px solid #555;
}
label {
  width: 100%;
}
#form input {
  width: 100%;
  height: 40px;
  padding: 0 30px 0 5px;
  border: 2px solid #c4c4c4;
  border-radius: 8px;
  outline: none;
}

#form input::placeholder {
  font: 1.25em sans-serif;
}
</style>

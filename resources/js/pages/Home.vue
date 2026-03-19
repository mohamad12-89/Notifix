<template>
  <div class="page">

    <!-- 🔷 NAVBAR -->
    <div class="navbar">

      <!-- 🖼 LOGO (top left) -->
      <!-- Replace the src later with your logo URL -->
      <img 
        src="" 
        alt="Logo" 
        class="logo"
      />

      <!-- 🧭 NAV BUTTONS -->
      <div class="nav-buttons">
        <button>Account</button>
        <button>TA Bios</button>
        <button>Appointments</button>
        <button>Office Hours</button>
      </div>

    </div>

    <!-- 🏷 TITLE -->
    <h1 class="title">Notifix</h1>

    <!-- 📅 WEEKLY SCHEDULE -->
    <div class="schedule">

      <h2>Weekly Office Hours</h2>

      <!-- Table -->
      <table>
        <thead>
          <tr>
            <th>TA Name</th>
            <th>Time</th>
            <th>Building</th>
            <th>Room</th>
            <th>Students</th>
          </tr>
        </thead>

        <tbody>
          <!-- Dummy data (you can change later) -->
          <tr>
            <td>John Smith</td>
            <td>Mon 2–4 PM</td>
            <td>Rice Hall</td>
            <td>101</td>
            <td>3</td>
          </tr>

          <tr>
            <td>Emily Chen</td>
            <td>Tue 10–12 PM</td>
            <td>Thornton Hall</td>
            <td>205</td>
            <td>5</td>
          </tr>

          <tr>
            <td>Michael Lee</td>
            <td>Wed 1–3 PM</td>
            <td>Olsson Hall</td>
            <td>120</td>
            <td>2</td>
          </tr>

        </tbody>
      </table>

    </div>

  </div>
</template>

<script>
export default {
  name: "Home"
}
</script>

<style scoped>

/* 🔷 PAGE BACKGROUND (UVA style) */
.page {
  min-height: 100vh;
  background: linear-gradient(to bottom right, #232d4b, #f84c1e);
  color: white;
  font-family: Arial, sans-serif;
}

/* 🧭 NAVBAR */
.navbar {
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
  padding: 20px;
}

/* 🖼 LOGO */
.logo {
  position: absolute;
  left: 20px;
  width: 50px;
  height: 50px;
  background-color: white; /* placeholder */
}

/* 🔘 NAV BUTTONS */
.nav-buttons button {
  margin: 0 10px;
  padding: 10px 18px;
  background-color: white;
  color: #232d4b;
  border: none;
  border-radius: 6px;
  cursor: pointer;
  font-weight: bold;
}

.nav-buttons button:hover {
  background-color: #f0f0f0;
}

/* 🏷 TITLE */
.title {
  text-align: center;
  font-size: 48px;
  margin-top: 10px;
}

/* 📅 SCHEDULE BOX */
.schedule {
  margin: 40px auto;
  width: 80%;
  background-color: white;
  color: black;
  padding: 20px;
  border-radius: 10px;
}

/* TABLE */
table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 20px;
}

th {
  background-color: #232d4b;
  color: white;
  padding: 10px;
}

td {
  padding: 10px;
  text-align: center;
  border-bottom: 1px solid #ddd;
}

</style>

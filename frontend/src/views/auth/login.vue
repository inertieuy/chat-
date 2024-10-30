<script setup></script>

<template>
  <div class="hero bg-slate-500 min-h-screen">
    <div class="hero-content flex-col lg:flex-row-reverse">
      <div class="card bg-gray-800 w-full max-w-sm shrink-0 shadow-2xl">
        <form class="card-body">
          <div class="form-control">
            <label class="label">
              <span class="label-text">Email</span>
            </label>
            <input
              type="email"
              placeholder="email"
              class="input input-bordered"
              required
            />
          </div>
          <div class="form-control">
            <label class="label">
              <span class="label-text">Password</span>
            </label>
            <input
              type="password"
              placeholder="password"
              class="input input-bordered"
              required
            />
            <label class="label">
              <router-link
                :to="{ name: 'register' }"
                class="label-text-alt link link-hover"
                >Belum Punya Akun?</router-link
              >
            </label>
          </div>
          <div class="form-control mt-6">
            <button type="submit" class="btn btn-primary">Login</button>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

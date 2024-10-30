<script>
import { createWebHistory, createRouter } from 'vue-router';

const routes = [
  {
    path: '/',
    name: 'home',
    component: () => import('../views/home/home.vue'),
  },
  {
    path: '/login',
    name: 'login',
    component: () => import('../views/auth/login.vue'),
  },
  {
    path: '/register',
    name: 'register',
    component: () => import('../views/auth/register.vue'),
  },
  {
    path: '/user/dashboard',
    name: 'dashboard',
    component: () => import('../views/user/dashboard.vue'),
  },
];

const router = createRouter({
  history: createWebHistory(),
  routes,
});

export default router;
</script>

<template>
  <div>
    <!-- Header -->
    <Header />
    <div class="px-5 py-3 lg:grid lg:grid-cols-12 lg:gap-10">
      <!-- Sidebar -->
      <Sidebar class="hidden lg:col-span-2 lg:block" />

      <!-- Main Section -->
      <main class="py-5 lg:col-span-6">
        <!-- Status Cards -->
        <StatusCard />
        <!-- New customer list -->
        <NewCustomers />
        <!-- Charts -->
        <SalesChart />
        <!-- Recent orders -->
        <RecentOrders />
      </main>
      <div class="hidden py-5 lg:col-span-3 lg:block">
        <!-- Profile info to the side -->
        <ProfileInfo />
        <hr class="my-5" />
        <!-- Reminders to the side -->
        <Reminders />
      </div>
    </div>
  </div>
</template>

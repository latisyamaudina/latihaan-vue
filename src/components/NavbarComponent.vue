<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar>
      <template #logo>
        <NavbarLogo link="https://www.google.com/" alt="Flowbite logo" image-url="https://media.istockphoto.com/id/1446858841/id/vektor/desain-logo-koki-logo-restoran.jpg?s=1024x1024&w=is&k=20&c=B1j8RDrCtxfol84OKo93o3lSRSXZrnLOP1CSAP6Fx80=">
          TheResto  
        </NavbarLogo>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink isActive link="#">Home</NavbarLink>
          <NavbarLink link="#">Menu</NavbarLink>
          <NavbarLink link="#">Contact</NavbarLink>
        </NavbarCollapse>
      </template>
    </Navbar>
</template>

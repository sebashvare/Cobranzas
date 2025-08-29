<script lang="ts">
    import { slide } from 'svelte/transition';
  
    let menuOpen = false;
  
    // Cerrar con Esc
    function onKeydown(e: KeyboardEvent) {
      if (e.key === 'Escape') menuOpen = false;
    }
   
</script>
<div class="relative flex size-full min-h-screen flex-col bg-[#141414] dark group/design-root overflow-x-hidden" style='font-family: Manrope, "Noto Sans", sans-serif;'>
    <div class="layout-container flex h-full grow flex-col">
    <header
        class="flex items-center justify-between whitespace-nowrap border-b border-solid border-b-[#214a3c] px-4 md:px-10 py-3"
        on:keydown={onKeydown}
      >
        <!-- Marca -->
        <div class="flex items-center gap-4 text-white">
          <div class="size-4">
            <!-- (tu svg intacto) -->
            <!-- ... -->
          </div>
          <h2 class="text-white text-lg font-bold leading-tight tracking-[-0.015em] uppercase">Avanza</h2>
        </div>
      
        <!-- Botón hamburguesa (solo móvil) -->
        <button
          class="md:hidden inline-flex items-center justify-center rounded-md p-2 text-white focus:outline-none focus:ring-2 focus:ring-[#019863]"
          aria-controls="primary-nav"
          aria-expanded={menuOpen}
          on:click={() => (menuOpen = !menuOpen)}
        >
          {#if !menuOpen}
            <!-- Icono abrir -->
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
            </svg>
          {:else}
            <!-- Icono cerrar -->
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
            </svg>
          {/if}
        </button>
      
        <!-- Zona derecha (desktop) -->
        <div class="hidden md:flex flex-1 justify-end gap-8">
          <div class="flex items-center gap-9 uppercase">
            <a class="text-white text-sm font-medium leading-normal" href="/">Dashboard</a>
            <a class="text-white text-sm font-medium leading-normal" href="/pagos">Préstamos</a>
            <a class="text-white text-sm font-medium leading-normal" href="/listado-usuario">Usuarios</a>
            <a class="text-white text-sm font-medium leading-normal" href="/">Pagos</a>
            <a class="text-white text-sm font-medium leading-normal" href="/">Perfil</a>
          </div>
      
          <div class="flex gap-2">
            <button
              class="flex max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 bg-[#214a3c] text-white gap-2 text-sm font-bold leading-normal tracking-[0.015em] min-w-0 px-2.5"
            >
              <div class="text-white" data-icon="Bell" data-size="20px" data-weight="regular">
                <svg xmlns="http://www.w3.org/2000/svg" width="20px" height="20px" fill="currentColor" viewBox="0 0 256 256">
                  <path
                    d="M221.8,175.94C216.25,166.38,208,139.33,208,104a80,80,0,1,0-160,0c0,35.34-8.26,62.38-13.81,71.94A16,16,0,0,0,48,200H88.81a40,40,0,0,0,78.38,0H208a16,16,0,0,0,13.8-24.06ZM128,216a24,24,0,0,1-22.62-16h45.24A24,24,0,0,1,128,216ZM48,184c7.7-13.24,16-43.92,16-80a64,64,0,1,1,128,0c0,36.05,8.28,66.73,16,80Z"
                  ></path>
                </svg>
              </div>
            </button>
            <button
              class="flex max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 bg-[#214a3c] text-white gap-2 text-sm font-bold leading-normal tracking-[0.015em] min-w-0 px-2.5"
            >
              <div class="text-white" data-icon="Moon" data-size="20px" data-weight="regular">
                <svg xmlns="http://www.w3.org/2000/svg" width="20px" height="20px" fill="currentColor" viewBox="0 0 256 256">
                  <path
                    d="M233.54,142.23a8,8,0,0,0-8-2,88.08,88.08,0,0,1-109.8-109.8,8,8,0,0,0-10-10,104.84,104.84,0,0,0-52.91,37A104,104,0,0,0,136,224a103.09,103.09,0,0,0,62.52-20.88,104.84,104.84,0,0,0,37-52.91A8,8,0,0,0,233.54,142.23ZM188.9,190.34A88,88,0,0,1,65.66,67.11a89,89,0,0,1,31.4-26A106,106,0,0,0,96,56,104.11,104.11,0,0,0,200,160a106,106,0,0,0,14.92-1.06A89,89,0,0,1,188.9,190.34Z"
                  ></path>
                </svg>
              </div>
            </button>
          </div>
      
          <div
            class="bg-center bg-no-repeat aspect-square bg-cover rounded-full size-10"
            style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuB441lSdVDQMhW2yglKhRfErjVF90JuSMt6qB5tECIewFe6i7TCv19cGl10_t6oqzEx72MZQUbXgBGnxwLaVwl9hucQb-PNNuMbR-WEKy13AnjJp2hIl0fA0KvKhheX66V1PTtiABcVlJ1FXZOMEOqcrqCjb4e1nLqnVgyAhKzRmiJsRmF3kiggPS75VMfZyn923vDHw-HFd6rEZk4aAwKwfmxW58lShMM-uzctjm2ObPi7Vo_1R85F37H_60QyYGh-YR1CsvW2G9w");'
          />
        </div>
    </header>
    {#if menuOpen}
  <nav
    id="primary-nav"
    class="md:hidden border-b border-[#214a3c] bg-[#10231c]"
    transition:slide
  >
    <div class="px-4 py-3 flex flex-col gap-4 uppercase">
      <a class="text-white text-sm font-medium leading-normal" href="/dashboard" on:click={() => (menuOpen = false)}>Inicio</a>
      <a class="text-white text-sm font-medium leading-normal" href="/pagos" on:click={() => (menuOpen = false)}>Préstamos</a>
      <a class="text-white text-sm font-medium leading-normal" href="/listado-usuario" on:click={() => (menuOpen = false)}>Usuarios</a>
      <a class="text-white text-sm font-medium leading-normal" href="/" on:click={() => (menuOpen = false)}>Perfil</a>

      <div class="flex gap-2">
        <button class="flex max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 bg-[#214a3c] text-white gap-2 text-sm font-bold leading-normal tracking-[0.015em] min-w-0 px-2.5">
          <div class="text-white" data-icon="Bell" data-size="20px" data-weight="regular">
            <svg xmlns="http://www.w3.org/2000/svg" width="20px" height="20px" fill="currentColor" viewBox="0 0 256 256">
              <path
                d="M221.8,175.94C216.25,166.38,208,139.33,208,104a80,80,0,1,0-160,0c0,35.34-8.26,62.38-13.81,71.94A16,16,0,0,0,48,200H88.81a40,40,0,0,0,78.38,0H208a16,16,0,0,0,13.8-24.06ZM128,216a24,24,0,0,1-22.62-16h45.24A24,24,0,0,1,128,216ZM48,184c7.7-13.24,16-43.92,16-80a64,64,0,1,1,128,0c0,36.05,8.28,66.73,16,80Z"
              ></path>
            </svg>
          </div>
        </button>
        <button
          class="flex max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 bg-[#214a3c] text-white gap-2 text-sm font-bold leading-normal tracking-[0.015em] min-w-0 px-2.5"
          on:click={channgeColor}
        >
          <div class="text-white" data-icon="Moon" data-size="20px" data-weight="regular">
            <svg xmlns="http://www.w3.org/2000/svg" width="20px" height="20px" fill="currentColor" viewBox="0 0 256 256">
              <path
                d="M233.54,142.23a8,8,0,0,0-8-2,88.08,88.08,0,0,1-109.8-109.8,8,8,0,0,0-10-10,104.84,104.84,0,0,0-52.91,37A104,104,0,0,0,136,224a103.09,103.09,0,0,0,62.52-20.88,104.84,104.84,0,0,0,37-52.91A8,8,0,0,0,233.54,142.23ZM188.9,190.34A88,88,0,0,1,65.66,67.11a89,89,0,0,1,31.4-26A106,106,0,0,0,96,56,104.11,104.11,0,0,0,200,160a106,106,0,0,0,14.92-1.06A89,89,0,0,1,188.9,190.34Z"
              ></path>
            </svg>
          </div>
        </button>
      </div>
    </div>
  </nav>
{/if}
    <div class="px-40 flex flex-1 justify-center py-5">
        <slot/>
      </div>
    </div>
</div>

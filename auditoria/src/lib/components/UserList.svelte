<div class="px-40 flex flex-1 justify-center py-5">
    <div class="layout-content-container flex flex-col max-w-[960px] flex-1">
      <div class="flex flex-wrap justify-between gap-3 p-4">
        <p class="text-white tracking-light text-[32px] font-bold leading-tight min-w-72 uppercase">Listado Usuarios</p>
        <div class="flex px-4 py-3 justify-end">
            <a class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 px-4 bg-[#019863] text-white text-sm font-bold leading-normal tracking-[0.015em]" href="usuarios">
              <span class="truncate">Crear Usuario</span>
            </a>
          </div>
      </div>
      <div class="px-4 py-3">
        <label class="flex flex-col min-w-40 h-12 w-full">
          <div class="flex w-full flex-1 items-stretch rounded-lg h-full">
            <div
              class="text-[#96c5a8] flex border-none bg-[#264532] items-center justify-center pl-4 rounded-l-lg border-r-0"
              data-icon="MagnifyingGlass"
              data-size="24px"
              data-weight="regular"
            >
              <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                <path
                  d="M229.66,218.34l-50.07-50.06a88.11,88.11,0,1,0-11.31,11.31l50.06,50.07a8,8,0,0,0,11.32-11.32ZM40,112a72,72,0,1,1,72,72A72.08,72.08,0,0,1,40,112Z"
                ></path>
              </svg>
            </div>
            <input
              placeholder="Buscar clientes..."
              class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-lg text-white focus:outline-0 focus:ring-0 border-none bg-[#264532] focus:border-none h-full placeholder:text-[#96c5a8] px-4 rounded-l-none border-l-0 pl-2 text-base font-normal leading-normal"
              value=""
            />
          </div>
        </label>
      </div>
      <div class="px-4 py-3 @container">
        <div class="flex overflow-hidden rounded-lg border border-[#366347] bg-[#122118]">
          <table class="flex-1">
            <thead>
              <tr class="bg-[#1b3124]">
                <th class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-120 px-4 py-3 text-left text-white w-[400px] text-sm font-medium leading-normal">Nombre</th>
                <th class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-240 px-4 py-3 text-left text-white w-[400px] text-sm font-medium leading-normal">
                  Identificación
                </th>
                <th class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-360 px-4 py-3 text-left text-white w-[400px] text-sm font-medium leading-normal">
                  Correo Electrónico
                </th>
                <th class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-480 px-4 py-3 text-left text-white w-[400px] text-sm font-medium leading-normal">Teléfono</th>
                <th class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-600 px-4 py-3 text-left text-white w-[400px] text-sm font-medium leading-normal">Dirección</th>
                <th class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-720 px-4 py-3 text-left text-white w-60 text-[#96c5a8] text-sm font-medium leading-normal">
                  Acciones
                </th>
              </tr>
            </thead>
            <tbody>
              <tr class="border-t border-t-[#366347]">
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-120 h-[72px] px-4 py-2 w-[400px] text-white text-sm font-normal leading-normal">
                  Sofía Rodríguez
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-240 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  1234567890
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-360 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  sofia.rodriguez@email.com
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-480 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  555-123-4567
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-600 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  Calle Principal 123, Ciudad
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-720 h-[72px] px-4 py-2 w-60 text-[#96c5a8] text-sm font-bold leading-normal tracking-[0.015em]">
                  Editar | Eliminar
                </td>
              </tr>
              <tr class="border-t border-t-[#366347]">
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-120 h-[72px] px-4 py-2 w-[400px] text-white text-sm font-normal leading-normal">Carlos López</td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-240 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  0987654321
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-360 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  carlos.lopez@email.com
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-480 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  555-987-6543
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-600 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  Avenida Central 456, Pueblo
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-720 h-[72px] px-4 py-2 w-60 text-[#96c5a8] text-sm font-bold leading-normal tracking-[0.015em]">
                  Editar | Eliminar
                </td>
              </tr>
              <tr class="border-t border-t-[#366347]">
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-120 h-[72px] px-4 py-2 w-[400px] text-white text-sm font-normal leading-normal">Ana Martínez</td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-240 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  1122334455
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-360 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  ana.martinez@email.com
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-480 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  555-111-2222
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-600 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  Plaza Mayor 789, Villa
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-720 h-[72px] px-4 py-2 w-60 text-[#96c5a8] text-sm font-bold leading-normal tracking-[0.015em]">
                  Editar | Eliminar
                </td>
              </tr>
              <tr class="border-t border-t-[#366347]">
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-120 h-[72px] px-4 py-2 w-[400px] text-white text-sm font-normal leading-normal">Diego García</td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-240 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  6677889900
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-360 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  diego.garcia@email.com
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-480 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  555-333-4444
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-600 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  Camino Real 101, Campo
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-720 h-[72px] px-4 py-2 w-60 text-[#96c5a8] text-sm font-bold leading-normal tracking-[0.015em]">
                  Editar | Eliminar
                </td>
              </tr>
              <tr class="border-t border-t-[#366347]">
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-120 h-[72px] px-4 py-2 w-[400px] text-white text-sm font-normal leading-normal">Laura Pérez</td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-240 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  2244668800
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-360 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  laura.perez@email.com
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-480 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  555-555-6666
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-600 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  Ruta del Sol 202, Playa
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-720 h-[72px] px-4 py-2 w-60 text-[#96c5a8] text-sm font-bold leading-normal tracking-[0.015em]">
                    <button class="flex max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 bg-[#214a3c] text-white gap-2 text-sm font-bold leading-normal tracking-[0.015em] min-w-0 px-2.5">
                        <div class="text-white" data-icon="bell" data-size="20px" data-weight="regular">
                          <svg xmlns="http://www.w3.org/2000/svg" width="20px" height="20px" fill="currentColor" viewBox="0 0 256 256">
                            <path
                              d="M221.8,175.94C216.25,166.38,208,139.33,208,104a80,80,0,1,0-160,0c0,35.34-8.26,62.38-13.81,71.94A16,16,0,0,0,48,200H88.81a40,40,0,0,0,78.38,0H208a16,16,0,0,0,13.8-24.06ZM128,216a24,24,0,0,1-22.62-16h45.24A24,24,0,0,1,128,216ZM48,184c7.7-13.24,16-43.92,16-80a64,64,0,1,1,128,0c0,36.05,8.28,66.73,16,80Z"
                            ></path>
                          </svg>
                        </div>
                      </button>
                </td>
              </tr>
              <tr class="border-t border-t-[#366347]">
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-120 h-[72px] px-4 py-2 w-[400px] text-white text-sm font-normal leading-normal">
                  Javier Sánchez
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-240 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  3355779911
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-360 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  javier.sanchez@email.com
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-480 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  555-777-8888
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-600 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  Vereda Alta 303, Montaña
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-720 h-[72px] px-4 py-2 w-60 text-[#96c5a8] text-sm font-bold leading-normal tracking-[0.015em]">
                  Editar | Eliminar
                </td>
              </tr>
              <tr class="border-t border-t-[#366347]">
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-120 h-[72px] px-4 py-2 w-[400px] text-white text-sm font-normal leading-normal">
                  Isabel Fernández
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-240 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  4466880022
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-360 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  isabel.fernandez@email.com
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-480 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  555-999-0000
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-600 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  Sendero Verde 404, Bosque
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-720 h-[72px] px-4 py-2 w-60 text-[#96c5a8] text-sm font-bold leading-normal tracking-[0.015em]">
                  Editar | Eliminar
                </td>
              </tr>
              <tr class="border-t border-t-[#366347]">
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-120 h-[72px] px-4 py-2 w-[400px] text-white text-sm font-normal leading-normal">
                  Miguel Ramírez
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-240 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  5577991133
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-360 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  miguel.ramirez@email.com
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-480 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  555-222-3333
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-600 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  Arroyo Claro 505, Río
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-720 h-[72px] px-4 py-2 w-60 text-[#96c5a8] text-sm font-bold leading-normal tracking-[0.015em]">
                  Editar | Eliminar
                </td>
              </tr>
              <tr class="border-t border-t-[#366347]">
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-120 h-[72px] px-4 py-2 w-[400px] text-white text-sm font-normal leading-normal">Carmen Ruiz</td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-240 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  6688002244
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-360 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  carmen.ruiz@email.com
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-480 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  555-444-5555
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-600 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  Quebrada Honda 606, Valle
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-720 h-[72px] px-4 py-2 w-60 text-[#96c5a8] text-sm font-bold leading-normal tracking-[0.015em]">
                  Editar | Eliminar
                </td>
              </tr>
              <tr class="border-t border-t-[#366347]">
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-120 h-[72px] px-4 py-2 w-[400px] text-white text-sm font-normal leading-normal">
                  Roberto Torres
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-240 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  7799113355
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-360 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  roberto.torres@email.com
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-480 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  555-666-7777
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-600 h-[72px] px-4 py-2 w-[400px] text-[#96c5a8] text-sm font-normal leading-normal">
                  Loma Serena 707, Colina
                </td>
                <td class="table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-720 h-[72px] px-4 py-2 w-60 text-[#96c5a8] text-sm font-bold leading-normal tracking-[0.015em]">
                  Editar | Eliminar
                </td>
              </tr>
            </tbody>
          </table>
        </div>
        <style>
          @container(max-width:120px){.table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-120{display: none;}}
          @container(max-width:240px){.table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-240{display: none;}}
          @container(max-width:360px){.table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-360{display: none;}}
          @container(max-width:480px){.table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-480{display: none;}}
          @container(max-width:600px){.table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-600{display: none;}}
          @container(max-width:720px){.table-1733fcb7-18a6-4108-a369-dfb54227fb87-column-720{display: none;}}
        </style>
      </div>
    </div>
</div>
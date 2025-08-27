<div class="layout-content-container flex flex-col max-w-[960px] flex-1">
    <div class="flex flex-wrap justify-between gap-3 p-4"><p class="text-white tracking-light text-[32px] font-bold leading-tight min-w-72">Gestión de Pagos</p></div>
    <h3 class="text-white text-lg font-bold leading-tight tracking-[-0.015em] px-4 pb-2 pt-4">Información del Cliente</h3>
    <div class="p-4 grid grid-cols-2">
      <div class="flex flex-col gap-1 border-t border-solid border-t-[#2f6a55] py-4 pr-2">
        <p class="text-[#8ecdb7] text-sm font-normal leading-normal">Nombre</p>
        <p class="text-white text-sm font-normal leading-normal">Lucia Rodriguez</p>
      </div>
      <div class="flex flex-col gap-1 border-t border-solid border-t-[#2f6a55] py-4 pl-2">
        <p class="text-[#8ecdb7] text-sm font-normal leading-normal">Identificación</p>
        <p class="text-white text-sm font-normal leading-normal">987654321</p>
      </div>
      <div class="flex flex-col gap-1 border-t border-solid border-t-[#2f6a55] py-4 pr-2">
        <p class="text-[#8ecdb7] text-sm font-normal leading-normal">Fecha de Creación</p>
        <p class="text-white text-sm font-normal leading-normal">20/03/2023</p>
      </div>
      <div class="flex flex-col gap-1 border-t border-solid border-t-[#2f6a55] py-4 pl-2">
        <p class="text-[#8ecdb7] text-sm font-normal leading-normal">Cantidad de Préstamos</p>
        <p class="text-white text-sm font-normal leading-normal">2</p>
      </div>
    </div>
    <h3 class="text-white text-lg font-bold leading-tight tracking-[-0.015em] px-4 pb-2 pt-4">Realizar Pago Parcial</h3>
    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
      <label class="flex flex-col min-w-40 flex-1">
        <p class="text-white text-base font-medium leading-normal pb-2">Monto a Pagar</p>
        <input
          placeholder="Ingrese el monto"
          class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-white focus:outline-0 focus:ring-0 border-none bg-[#214a3c] focus:border-none h-14 placeholder:text-[#8ecdb7] p-4 text-base font-normal leading-normal"
          value=""
        />
      </label>
    </div>
    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
      <label class="flex flex-col min-w-40 flex-1">
        <p class="text-white text-base font-medium leading-normal pb-2">Número de Cuotas a Abonar</p>
        <input
          placeholder="Ingrese el número de cuotas"
          class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-white focus:outline-0 focus:ring-0 border-none bg-[#214a3c] focus:border-none h-14 placeholder:text-[#8ecdb7] p-4 text-base font-normal leading-normal"
          value=""
        />
      </label>
    </div>
    <div class="flex px-4 py-3 justify-end">
      <button
        class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 px-4 bg-[#019863] text-white text-sm font-bold leading-normal tracking-[0.015em]"
      >
        <span class="truncate">Realizar Pago</span>
      </button>
    </div>
    <div class="pb-3">
      <div class="flex border-b border-[#2f6a55] px-4 gap-8">
        <a class="flex flex-col items-center justify-center border-b-[3px] border-b-[#019863] text-white pb-[13px] pt-4" href="#">
          <p class="text-white text-sm font-bold leading-normal tracking-[0.015em]">Historial de Pagos</p>
        </a>
        <a class="flex flex-col items-center justify-center border-b-[3px] border-b-transparent text-[#8ecdb7] pb-[13px] pt-4" href="#">
          <p class="text-[#8ecdb7] text-sm font-bold leading-normal tracking-[0.015em]">Información del Cliente</p>
        </a>
        <a class="flex flex-col items-center justify-center border-b-[3px] border-b-transparent text-[#8ecdb7] pb-[13px] pt-4" href="#">
          <p class="text-[#8ecdb7] text-sm font-bold leading-normal tracking-[0.015em]">Documentos</p>
        </a>
      </div>
    </div>
    <div class="px-4 py-3 @container">
      <div class="flex overflow-hidden rounded-xl border border-[#2f6a55] bg-[#10231c]">
        <table class="flex-1">
          <thead>
            <tr class="bg-[#17352b]">
              <th class="table-b30a86f4-3a67-4ceb-8d9f-39f5686f96b9-column-120 px-4 py-3 text-left text-white w-[400px] text-sm font-medium leading-normal">Fecha</th>
              <th class="table-b30a86f4-3a67-4ceb-8d9f-39f5686f96b9-column-240 px-4 py-3 text-left text-white w-[400px] text-sm font-medium leading-normal">
                Monto Pagado
              </th>
              <th class="table-b30a86f4-3a67-4ceb-8d9f-39f5686f96b9-column-360 px-4 py-3 text-left text-white w-[400px] text-sm font-medium leading-normal">
                Cuotas Abonadas
              </th>
            </tr>
          </thead>
          <tbody>
            <tr class="border-t border-t-[#2f6a55]">
              <td class="table-b30a86f4-3a67-4ceb-8d9f-39f5686f96b9-column-120 h-[72px] px-4 py-2 w-[400px] text-[#8ecdb7] text-sm font-normal leading-normal">
                15/07/2024
              </td>
              <td class="table-b30a86f4-3a67-4ceb-8d9f-39f5686f96b9-column-240 h-[72px] px-4 py-2 w-[400px] text-[#8ecdb7] text-sm font-normal leading-normal">$500</td>
              <td class="table-b30a86f4-3a67-4ceb-8d9f-39f5686f96b9-column-360 h-[72px] px-4 py-2 w-[400px] text-[#8ecdb7] text-sm font-normal leading-normal">2</td>
            </tr>
            <tr class="border-t border-t-[#2f6a55]">
              <td class="table-b30a86f4-3a67-4ceb-8d9f-39f5686f96b9-column-120 h-[72px] px-4 py-2 w-[400px] text-[#8ecdb7] text-sm font-normal leading-normal">
                01/07/2024
              </td>
              <td class="table-b30a86f4-3a67-4ceb-8d9f-39f5686f96b9-column-240 h-[72px] px-4 py-2 w-[400px] text-[#8ecdb7] text-sm font-normal leading-normal">$250</td>
              <td class="table-b30a86f4-3a67-4ceb-8d9f-39f5686f96b9-column-360 h-[72px] px-4 py-2 w-[400px] text-[#8ecdb7] text-sm font-normal leading-normal">1</td>
            </tr>
            <tr class="border-t border-t-[#2f6a55]">
              <td class="table-b30a86f4-3a67-4ceb-8d9f-39f5686f96b9-column-120 h-[72px] px-4 py-2 w-[400px] text-[#8ecdb7] text-sm font-normal leading-normal">
                15/06/2024
              </td>
              <td class="table-b30a86f4-3a67-4ceb-8d9f-39f5686f96b9-column-240 h-[72px] px-4 py-2 w-[400px] text-[#8ecdb7] text-sm font-normal leading-normal">$500</td>
              <td class="table-b30a86f4-3a67-4ceb-8d9f-39f5686f96b9-column-360 h-[72px] px-4 py-2 w-[400px] text-[#8ecdb7] text-sm font-normal leading-normal">2</td>
            </tr>
            <tr class="border-t border-t-[#2f6a55]">
              <td class="table-b30a86f4-3a67-4ceb-8d9f-39f5686f96b9-column-120 h-[72px] px-4 py-2 w-[400px] text-[#8ecdb7] text-sm font-normal leading-normal">
                01/06/2024
              </td>
              <td class="table-b30a86f4-3a67-4ceb-8d9f-39f5686f96b9-column-240 h-[72px] px-4 py-2 w-[400px] text-[#8ecdb7] text-sm font-normal leading-normal">$250</td>
              <td class="table-b30a86f4-3a67-4ceb-8d9f-39f5686f96b9-column-360 h-[72px] px-4 py-2 w-[400px] text-[#8ecdb7] text-sm font-normal leading-normal">1</td>
            </tr>
            <tr class="border-t border-t-[#2f6a55]">
              <td class="table-b30a86f4-3a67-4ceb-8d9f-39f5686f96b9-column-120 h-[72px] px-4 py-2 w-[400px] text-[#8ecdb7] text-sm font-normal leading-normal">
                15/05/2024
              </td>
              <td class="table-b30a86f4-3a67-4ceb-8d9f-39f5686f96b9-column-240 h-[72px] px-4 py-2 w-[400px] text-[#8ecdb7] text-sm font-normal leading-normal">$500</td>
              <td class="table-b30a86f4-3a67-4ceb-8d9f-39f5686f96b9-column-360 h-[72px] px-4 py-2 w-[400px] text-[#8ecdb7] text-sm font-normal leading-normal">2</td>
            </tr>
          </tbody>
        </table>
      </div>
      <style>
        @container(max-width:120px){.table-b30a86f4-3a67-4ceb-8d9f-39f5686f96b9-column-120{display: none;}}
        @container(max-width:240px){.table-b30a86f4-3a67-4ceb-8d9f-39f5686f96b9-column-240{display: none;}}
        @container(max-width:360px){.table-b30a86f4-3a67-4ceb-8d9f-39f5686f96b9-column-360{display: none;}}
      </style>
    </div>
  </div>
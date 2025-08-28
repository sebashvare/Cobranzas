<div class="layout-content-container flex flex-col max-w-[960px]">
    <div class="flex flex-wrap justify-between gap-3 p-4">
        <p class="text-white tracking-light text-[32px] font-bold leading-tight min-w-72">
            Agregar Nuevo Cliente
        </p>
    </div>
    <div class="p-4 grid grid-cols-1 justify-center items-center">
        <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
        <label class="flex flex-col min-w-40 flex-1">
            <p class="text-white text-base font-medium leading-normal pb-2">
                Nombre
            </p>
            <input
                placeholder="Ingrese el nombre del cliente"
                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-white focus:outline-0 focus:ring-0 border-none bg-[#2f6a55] focus:border-none h-14 placeholder:text-[#ababab] p-4 text-base font-normal leading-normal"
                value=""
            />
        </label>
    </div>
    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
        <label class="flex flex-col min-w-40 flex-1">
            <p class="text-white text-base font-medium leading-normal pb-2">
                Identificación
            </p>
            <input
                placeholder="Ingrese el número de identificación del cliente"
                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-white focus:outline-0 focus:ring-0 border-none bg-[#2f6a55] focus:border-none h-14 placeholder:text-[#ababab] p-4 text-base font-normal leading-normal"
                value=""
            />
        </label>
    </div>
    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
        <label class="flex flex-col min-w-40 flex-1">
            <p class="text-white text-base font-medium leading-normal pb-2">
                Teléfono
            </p>
            <input 
                placeholder="Ingrese el número de teléfono del cliente"
                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-white focus:outline-0 focus:ring-0 border-none bg-[#2f6a55] focus:border-none h-14 placeholder:text-[#ababab] p-4 text-base font-normal leading-normal"
                value=""
            />
        </label>
    </div>
    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
        <label class="flex flex-col min-w-40 flex-1">
            <p class="text-white text-base font-medium leading-normal pb-2">
                Dirección
            </p>
            <input
                placeholder="Ingrese la dirección del cliente"
                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-white focus:outline-0 focus:ring-0 border-none bg-[#2f6a55] focus:border-none h-14 placeholder:text-[#ababab] p-4 text-base font-normal leading-normal"
                value=""
            />
        </label>
    </div>
    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
        <label class="flex flex-col min-w-40 flex-1">
            <p class="text-white text-base font-medium leading-normal pb-2">
                Dirección Laboral
            </p>
            <input
                placeholder="Ingrese la dirección laboral del cliente"
                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-white focus:outline-0 focus:ring-0 border-none bg-[#2f6a55] focus:border-none h-14 placeholder:text-[#ababab] p-4 text-base font-normal leading-normal"
                value=""
            />
        </label>
    </div>
    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
        <label class="flex flex-col min-w-40 flex-1">
            <p class="text-white text-base font-medium leading-normal pb-2">
                Email
            </p>
            <input
                placeholder="Ingrese el correo electrónico del cliente"
                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-white focus:outline-0 focus:ring-0 border-none bg-[#2f6a55] focus:border-none h-14 placeholder:text-[#ababab] p-4 text-base font-normal leading-normal"
                value=""
            />
        </label>
    </div>
    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
        <label class="flex flex-col min-w-40 flex-1">
            <p class="text-white text-base font-medium leading-normal pb-2">
                Redes Sociales
            </p>
            <input
                placeholder="Ingrese el usuario de redes sociales del cliente"
                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-white focus:outline-0 focus:ring-0 border-none bg-[#2f6a55] focus:border-none h-14 placeholder:text-[#ababab] p-4 text-base font-normal leading-normal"
                value=""
            />
        </label>
    </div>
    
    <div class="flex flex-col p-4">
        <div class="flex flex-col items-center gap-6 rounded-xl border-2 border-dashed border-[#2f6a55] px-6 py-14">
            <div class="flex max-w-[480px] flex-col items-center gap-2">
                <p class="text-white text-lg font-bold leading-tight tracking-[-0.015em] max-w-[480px] text-center">
                    Subir Foto del Cliente
                </p>
                <p class="text-white text-sm font-normal leading-normal max-w-[480px] text-center">
                    Arrastra y suelta o navega para subir
                </p>
            </div>
            <input type="file" class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 px-4 text-white text-sm font-bold leading-normal tracking-[0.015em] text-center" placeholder="Examinar"/>
            
        </div>
    </div>
    
    <div class="flex flex-col p-4">
        <div
            class="flex flex-col items-center gap-6 rounded-xl border-2 border-dashed border-[#2f6a55] px-6 py-14"
        >
            <div class="flex max-w-[480px] flex-col items-center gap-2">
                <p
                    class="text-white text-lg font-bold leading-tight tracking-[-0.015em] max-w-[480px] text-center"
                >
                    Subir Frontal de ID
                </p>
                <p
                    class="text-white text-sm font-normal leading-normal max-w-[480px] text-center"
                >
                    Arrastra y suelta o navega para subir
                </p>
            </div>
            <input type="file" class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 px-4 text-white text-sm font-bold leading-normal tracking-[0.015em] text-center" placeholder="Examinar"/>
        </div>
    </div>
    <div class="flex flex-col p-4 ">
        <div class="flex flex-col items-center gap-6 rounded-xl border-2 border-dashed border-[#2f6a55] px-6 py-14">
            <div class="flex max-w-[480px] flex-col items-center gap-2">
                <p class="text-white text-lg font-bold leading-tight tracking-[-0.015em] max-w-[480px] text-center">
                    Subir Posterior de ID
                </p>
                <p
                    class="text-white text-sm font-normal leading-normal max-w-[480px] text-center"
                >
                    Arrastra y suelta o navega para subir
                </p>
            </div>
            <input type="file" class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 px-4 text-white text-sm font-bold leading-normal tracking-[0.015em] text-center" placeholder="Examinar"/>
        </div>
    </div>
    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
        <label class="flex flex-col min-w-40 flex-1">
            <p class="text-white text-base font-medium leading-normal pb-2">
                Identificación del Fiador
            </p>
            <input
                placeholder="Ingrese el número de identificación del fiador"
                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-white focus:outline-0 focus:ring-0 border-none bg-[#2f6a55] focus:border-none h-14 placeholder:text-[#ababab] p-4 text-base font-normal leading-normal"
                value=""
            />
        </label>
    </div>
    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
        <label class="flex flex-col min-w-40 flex-1">
            <p class="text-white text-base font-medium leading-normal pb-2">
                Nombre del Fiador
            </p>
            <input
                placeholder="Ingrese el nombre del fiador"
                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-white focus:outline-0 focus:ring-0 border-none bg-[#2f6a55] focus:border-none h-14 placeholder:text-[#ababab] p-4 text-base font-normal leading-normal"
                value=""
            />
        </label>
    </div>
    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
        <label class="flex flex-col min-w-40 flex-1">
            <p class="text-white text-base font-medium leading-normal pb-2">
                Apellido del Fiador
            </p>
            <input
                placeholder="Ingrese el apellido del fiador"
                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-white focus:outline-0 focus:ring-0 border-none bg-[#2f6a55] focus:border-none h-14 placeholder:text-[#ababab] p-4 text-base font-normal leading-normal"
                value=""
            />
        </label>
    </div>
    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
        <label class="flex flex-col min-w-40 flex-1">
            <p class="text-white text-base font-medium leading-normal pb-2">
                Dirección del Fiador
            </p>
            <input
                placeholder="Ingrese la dirección del fiador"
                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-white focus:outline-0 focus:ring-0 border-none bg-[#2f6a55] focus:border-none h-14 placeholder:text-[#ababab] p-4 text-base font-normal leading-normal"
                value=""
            />
        </label>
    </div>
    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
        <label class="flex flex-col min-w-40 flex-1">
            <p class="text-white text-base font-medium leading-normal pb-2">
                Teléfono del Fiador
            </p>
            <input
                placeholder="Ingrese el número de teléfono del fiador"
                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-white focus:outline-0 focus:ring-0 border-none bg-[#2f6a55] focus:border-none h-14 placeholder:text-[#ababab] p-4 text-base font-normal leading-normal"
                value=""
            />
        </label>
    </div>
</div>
<div class="flex px-4 py-3 justify-end">
    <button
        class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 px-4 bg-[#2f6a55] text-white text-sm font-bold leading-normal tracking-[0.015em]"
    >
        <span class="truncate">Registrar Cliente</span>
    </button>
</div>
    
</div>

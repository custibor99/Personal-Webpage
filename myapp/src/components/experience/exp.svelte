<div class=" flex flex-col lg:flex-row border-2 border-red-500 py-3">
    <div class="table-cell border-2 border-blue-200 lg:w-1/3">
        <slot name="expMetadata">
            <p>Metadata box</p>
        </slot>

    </div>
    <div class="table-cell border-2 border-blue-200 lg:w-2/3">
        <slot name="expDescription">
            <p>Description box</p>
        </slot>
    </div>
</div>
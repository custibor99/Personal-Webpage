<div class=" flex flex-col lg:flex-row py-14 pt-10">
    <div class="table-cell lg:w-1/2">
        <slot name="expMetadata">
            <p>Metadata box</p>
        </slot>

    </div>
    <div class="table-cell lg:w-1/2 lg:pt-14">
        <slot name="expDescription">
            <p>Description box</p>
        </slot>
    </div>
</div>
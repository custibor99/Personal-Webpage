<script>
    import Exp from "./exp.svelte";
    import ExpMetadata from "./expMetadata.svelte";
    import IconEllj from "$lib/assets/ellj.png";
    import IconMerck from "$lib/assets/merck.png"
    import IconOutbrain from "$lib/assets/outbrain.png"
    import SectionWrapper from "../sectionWrapper.svelte";
    
</script>
<SectionWrapper sectionTitle="Experience">
    <Exp>
        <ExpMetadata slot="expMetadata">
            <img slot="img" src={IconEllj} alt="Elektro ljubljana d.o.o" class="w-20 h-20">
        </ExpMetadata>
        <ExpMetadata slot="expDescription"></ExpMetadata>
    </Exp>
    <Exp>
        <ExpMetadata slot="expMetadata">
            <img slot="img" src={IconMerck} alt="Elektro ljubljana d.o.o" class="w-20 h-20 py-5 px-3">
        </ExpMetadata>
        <ExpMetadata slot="expDescription"></ExpMetadata>
    </Exp>
    <Exp>
        <ExpMetadata slot="expMetadata">
            <img slot="img" src={IconOutbrain} alt="Elektro ljubljana d.o.o" class="w-20 h-20 p-3">
        </ExpMetadata>
        <ExpMetadata slot="expDescription"></ExpMetadata>
    </Exp>
</SectionWrapper>


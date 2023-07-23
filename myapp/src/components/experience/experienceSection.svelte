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
        <ExpMetadata slot="expMetadata" jobTitle="Data Engineer" companyName="Elektro Ljubljana d.o.o" location="Ljubljana" duration="Feb. 2021 - Feb. 2022">
            <img slot="img" src={IconEllj} alt="Elektro ljubljana d.o.o" class="w-20 h-20 min-h-20 min-h-20 aspect-square">
        </ExpMetadata>
        <div slot="expDescription" class="lg:pl-7 pl-36 pr-16">
            <ul class="list-disc">
                <li>Developing microservices in Java/Kotlin with springboot, whic are used for processing terabytes of data daily.</li>
                <li>Preparing data processing and reporting pipelines in BiqQuery with scheduled queries.</li>
                <li>Developing new features on our real-time programmatic advertising system written in Go.</li>
            </ul>
        </div>

    </Exp>
    <Exp>
        <ExpMetadata slot="expMetadata" jobTitle="Data scientist" companyName="Merck" location="Ljubljana" duration="May 2022 - March 2023">
            <img slot="img" src={IconMerck} alt="merck logo" class="w-20 h-20 py-5 px-3 min-h-20 min-h-20 aspect-square">
        </ExpMetadata>
        <ExpMetadata slot="expDescription"></ExpMetadata>
    </Exp>
    <Exp>
        <ExpMetadata slot="expMetadata" jobTitle="Software engineer" companyName="Outbrain" location="Ljubljana" duration="Oct 2022 - Present">
            <img slot="img" src={IconOutbrain} alt="outbrain logo" class="w-20 h-20 p-3 min-h-20 min-h-20 aspect-square">
        </ExpMetadata>
        <ExpMetadata slot="expDescription"></ExpMetadata>
    </Exp>
</SectionWrapper>


<script>
    import ProjectObject from "./projectObject.svelte";
    import SectionWrapper from "../sectionWrapper.svelte";
</script>

<SectionWrapper sectionTitle="Projects">
    <div class="grid grid-cols-1 lg:grid-cols-2 xl:grid-cols-2 2xl:grid-cols-3 gap-10 place-items-cente pt-5 pb-20">
        <ProjectObject title="Personal website" text="Personal website made in svelt and tailwind css"/>
        <ProjectObject title="Distributed file system" text="Distributed file system similar to HDFS written in GO"/>
        <ProjectObject title="Distributed file system" text="Distributed file system similar to HDFS written in GO"/>
        <!--
            <ProjectObject title="Distributed file system" text="Distributed file system similar to HDFS written in GO"/>
            <ProjectObject title="Data analytics in R" text="Collection of data analytics projects implemented in R"/>
            <ProjectObject title="Data analytics in Python" text="Collection of data analytics projects implemented Python"/>
            <ProjectObject title="GoML" text="Implementation of some machine learning algorithms written in GoLang"/>
        -->
    </div>
</SectionWrapper>


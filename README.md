# apache_beam_doc_ko
> 아파치 Beam 도큐멘테이션 번역  
>
> 역자주  
> [Apache beam](https://beam.apache.org/) documentations 를 번역한 글입니다. 공부 목적이니 마음껏 사용하세요 :)

## Contents

- **[Apache Beam Programming Guide](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/1.%20Apache%20Beam%20Programming%20Guide)**
    - [Overview](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/1.%20Apache%20Beam%20Programming%20Guide/1.%20Overview)
    - [Creating the Pipeline](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/1.%20Apache%20Beam%20Programming%20Guide/2.%20Creating%20the%20pipeline)
    - [Working with PCollections](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/1.%20Apache%20Beam%20Programming%20Guide/3.%20Working%20with%20PCollections)
        - [Creating a PCollection](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/1.%20Apache%20Beam%20Programming%20Guide/3.%20Working%20with%20PCollections/1.%20Creating%20a%20PCollection)
        - [PCollection Characteristics](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/1.%20Apache%20Beam%20Programming%20Guide/3.%20Working%20with%20PCollections/2.%20PCollection%20characteristics)
    - [Applying Transforms](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/1.%20Apache%20Beam%20Programming%20Guide/4.%20Applying%20transforms)
        - [Using ParDo](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/1.%20Apache%20Beam%20Programming%20Guide/4.%20Applying%20transforms/1.%20Using%20ParDo)
        - [Using GroupByKey](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/1.%20Apache%20Beam%20Programming%20Guide/4.%20Applying%20transforms/2.%20Using%20GroupByKey)
        - [Using Combine](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/1.%20Apache%20Beam%20Programming%20Guide/4.%20Applying%20transforms/3.%20Using%20Combine)
        - [Using Flatten and Partition](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/1.%20Apache%20Beam%20Programming%20Guide/4.%20Applying%20transforms/4.%20Using%20Flatten%20and%20Partition)
        - [General Requirements for Writing User Code for Beam Transforms](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/1.%20Apache%20Beam%20Programming%20Guide/4.%20Applying%20transforms/5.%20General%20Requirements%20for%20writing%20user%20code%20for%20Beam%20transforms)
        - [Side Inputs and Side Outputs](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/1.%20Apache%20Beam%20Programming%20Guide/4.%20Applying%20transforms/6.%20Side%20Inputs%20and%20Side%20Outputs)
    - [Composite Transforms](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/1.%20Apache%20Beam%20Programming%20Guide/5.%20Composite%20Transforms)
    - [Pipeline I/O](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/1.%20Apache%20Beam%20Programming%20Guide/6.%20Pipeline%20Input%20Output)
    - [Running the Pipeline](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/1.%20Apache%20Beam%20Programming%20Guide/7.%20Running%20the%20pipeline)
    - [Data Encoding and Type Safety](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/1.%20Apache%20Beam%20Programming%20Guide/8.%20Data%20encoding%20and%20type%20safety)
    - Working with Windowing (준비중)
    - Working with Triggers (준비중)

- **[Pipeline Fundamentals](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals)**
    - [Design Your Pipeline](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals/1.%20Design%20Your%20Pipeline)
        - [What to consider when designing your pipeline](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals/1.%20Design%20Your%20Pipeline/1.%20What%20to%20consider%20when%20designing%20your%20pipeline)
        - [A basic pipeline](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals/1.%20Design%20Your%20Pipeline/2.%20A%20basic%20pipeline)
        - [Branching PCollections](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals/1.%20Design%20Your%20Pipeline/3.%20Branching%20PCollections)
        - [Merging PCollections](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals/1.%20Design%20Your%20Pipeline/4.%20Merging%20PCollections)
        - [Multiple source](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals/1.%20Design%20Your%20Pipeline/5.%20Multiple%20sources)
        - [What's next](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals/1.%20Design%20Your%20Pipeline/6.%20What's%20next)
    - [Create Your Pipeline](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals/2.%20Create%20Your%20Pipeline)
        - [Creating Your Pipeline Object](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals/2.%20Create%20Your%20Pipeline/1.%20Creating%20Your%20Pipeline%20Obejct)
        - [Reading Data Into Your Pipeline](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals/2.%20Create%20Your%20Pipeline/2.%20Reading%20Data%20Into%20Your%20Pipeline)
        - [Applying Transforms to Process Pipeline Data](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals/2.%20Create%20Your%20Pipeline/3.%20Applying%20Transforms%20to%20Process%20Pipeline%20Data)
        - [Writing or Outputting Your Final Pipeline Data](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals/2.%20Create%20Your%20Pipeline/4.%20Writing%20or%20Outputting%20Your%20Final%20Pipeline%20Data)
        - [Running Your Pipeline](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals/2.%20Create%20Your%20Pipeline/5.%20Running%20Your%20Pipeline)
        - [What's next](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals/2.%20Create%20Your%20Pipeline/6.%20What's%20next)
    - [Test Your Pipeline](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals/3.%20Test%20Your%20Pipeline)
        - [Testing Individual DoFn Objects](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals/3.%20Test%20Your%20Pipeline/1.%20Testing%20Individual%20DoFn%20Objects)
            - [Creating a DoFnTester](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals/3.%20Test%20Your%20Pipeline/1.%20Testing%20Individual%20DoFn%20Objects#creating-a-dofntester)
            - [Creating Test Inputs](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals/3.%20Test%20Your%20Pipeline/1.%20Testing%20Individual%20DoFn%20Objects#creating-test-inputs)
                - [Side Inputs and Outputs](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals/3.%20Test%20Your%20Pipeline/1.%20Testing%20Individual%20DoFn%20Objects#side-inputs-and-outputs)
            - [Processing Test Inputs and Checking Results](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals/3.%20Test%20Your%20Pipeline/1.%20Testing%20Individual%20DoFn%20Objects#processing-test-inputs-and-checking-result)
        - [Testing Composite Transforms](https://github.com/sungjunyoung/apache_beam_doc_ko/tree/master/2.%20Pipeline%20Fundamentals/3.%20Test%20Your%20Pipeline/2.%20Testing%20Composite%20Transforms)
            - TestPipeline
            - Using the Create Transform
            - PAssert
            - An Example Test for a Composite Transform
        - Testing a Pipeline End-to-End
            - Testing the WordCount Pipeline

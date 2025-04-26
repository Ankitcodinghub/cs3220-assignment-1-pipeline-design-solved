# cs3220-assignment-1-pipeline-design-solved
**TO GET THIS SOLUTION VISIT:** [CS3220 Assignment #1 : Pipeline Design Solved](https://www.ankitcodinghub.com/product/cs3220-assignment-1-pipeline-design-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;126098&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS3220 Assignment #1 : Pipeline Design Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Part 1: (5 pts)

Part 2: (5 pts)

Part 3: (5 pts)

This is a two-member group project.

Description: In this assignment, you will design a RISC-V 5-stage pipelined processor using verilog. The ISA is a subset of RISC-V ISA. We will use Tiny RISC-V version from Cornell In part-1, you only need to implement addi, add, beq instruction to pass all 5 test cases in tests/part1/test[1-5].mem file. (a subset of TinyRV1). In part-2, you will add more instructions to test a subset of test suites. In part-3: you will complete TinyRV2 except CSR related instructions. You might add CSR instructions (CSRR, CSRW) in the later projects. I In this design, you don’t need to implement data forwarding in this part. The starting PC address is 0x200.

Part 1 : Minimal functionality

In this part, you will implement a subset of pipeline. You only need to pass 5 tests we created. Please see the test cases for the part-1 requirements. You can locate those test files under the tests directory. You can refer to the README file under tests for more information about each test case.

You do not need to implement forwarding in this assignment. Your program should run with test[1-5].mem file.

What to submit: ** A zip file of your source code. The zip file must contain the following:** type make submit will generate a submission.zip. Please submit the submission.zip file. Each submission for each group. If you don’t use Makefile, please execute the following command. zip submission.zip ./*.v ./*.h ./*.vh ./sim_main.cpp ./Makefile and submit submission.zip file. We strongly encourage for you to use Make submit command to generate the submission file so that it won’t break our autograding script.

Grading: Based on the coverage of test suites, you will get partial scores.

Please do not procrastinate.

Part 2: Pass a subset of RISC-V test suite

In this part, you will add more instructions in your pipeline to test RISC-V ISA. You need to pass the test cases in part-2 test suites. We will provide RISC-V test suite modified for our ISA to test your design. Testing all the test suits is for your debugging purpose. he test suite will be released soon.

Test cases: In part-2, all instructions in the test cases in part2 such as add, addi, auipc, beq, bge, (all branch instructions) jal, jalr instructions will be tested. you need to pass all test cases in test/part2 directory. To test all test cases together, you can use run_tests.sh part2 and it will produce part[1-3]_results.log and part[1-3]_tests.log. test[7-9] are hand written assembly code which is easier to debug. please use those test cases first. In part-2, we start to use modified RISC-V test suites. *.S is assembly code that takes RISC-V macro. Macro files are defined at include d/test_macros.h or include/riscv_test.h It also uses ABI names and Pseudo Instructions. You can find a summary of information [here] *.dump is an dump file output from gcc riscv compiler. *.mem file has the format for verilog code. *.dec file is useful to use [RISC-V emulator]

Grading: Based on the coverage of test suites, you will get partial scores.

Part 3: Complete the pipeline

Description: In this part, you will complete the pipeline to test RISC-V ISA (except CSR instructions). Your program should run with testall.mem case we provide. In this project, we will evaluate your design with only behavioral simulation.

Grading: If you pass all test cases under part3 folder (you need to see “Pass” ) you will get full credits. If you don’t pass all test cases located under part3 folder, you will get a partial grading based on the coverage of part 3 test suites.

What to submit: ** A zip file for your source code. The zip file must contain the following:** type make submit will generate a submission.zip.

Useful Information

References

RISC-V Assembly code summary of RISC-V Assembly coding RISC-V emulator (tiny RV2)

RISC-V emulator (full ISA support)

Verilator manual

GTKWave manual

Tutorial about RISC-V TEST SUITE

FAQ

(Q) How do I run a specific test file?

(A) Please see “define.vh”

You need to change “test1.mem” into “test2.mem” etc.

(Q) How do I know whether my implementation is correct or not?

(A) If you are using verilator, you would see “Pass” message.

(Q) Can I add new files?

(A) Yes, but please make sure they are added in the zip file.

(Q) Do we need to implement a branch predictor?

(A) It’s not required but you could implement an always not-taken branch predictor.

(Q) Do we need to create a stack for nested JAL instructions?

(A) The hardware does not know any nested calls. so you do not need to implement it.

(Q) BEQ t1, t1, imm : if a branch is taken, is the new PC = PC + imm or new PC = PC + 4+ imm?

(A) The answer is PC = PC + offset. Please be careful with converting imm to offset.

(Q) How to insert a bubble in the pipeline?

(A) You could have a valid bit for each pipeline latch to indicate whether the contents in the latch is valid or not (FE_valid, DE_valid, etc.). Or you could insert zeros to all latch contents. This is your implementation decision.

(Q) Do we need to worry whether we should prevent all writes to the zero register and treat it as always zero, or if that is solely up to us dependent on our design?

(A) This is purely S/W job. The H/W doesn’t have to check whether x0 is writable or not. The Hardware also doesn’t have explicitly insert 0 in hardware.

(Q) Debugging takes so much time. Any tips to reduce the debugging time?

(A) Some suggestions. 1. Review code carefully and understand the ISA behavior correctly 2. Verilator is faster to debug 3. Verilator provides an interface to access the verilog data structures. Please see under #ifdef DPRITF … in sim_main.cpp. and wb_stage.v to see an example of passing the contents of pipeline into c++ and use printf to debug.

1. Verilator generates vcd file. Please use GTKWave or other waveform viewer (Microsoft VSC provides trace viewer) to see each pipeline signal.

(Q) Is the immediate field inside assembly code decimal?

(A) If the number starts with 0x, it’s hexadecimal.

(Q) When we access the memory, why we drop out LSB 2 bits?

(A) ISA is byte addressability but the verilog imem/dmem is declared as if it is word addressability since we don’t do any unaligned accesses.

(Q) What does assign inst_FE = imem[PC_FE_latch[`IMEMADDRBITS-1:`IMEMWORDBITS]]; mean?

(A) PC_FE_latch contains PC value. again imem and dmem are word addressable. so we don’t need LSB 2 bits. Since imem and dmem has only 2^14 size, we just use addr [15:2] bits to index imem/dmem.

(Q) I want to generate more test cases. Do we have an assembler?

(A) If you want to generate more test cases, you can write sample assembly code using the following online assembler . Once you get the hexdump value, copy paste the contents into one of the test files starting from line 129. The reason is that the starting PC address is 0x200 (512). Each line in the mem (or hex) file contains 4B. readmemh function will read one line at a time and put 4B to four consecutive memory addresses. RISC-V is byte addressable but the readmemh (or imem in the vivado tool chain)’ interface is for word-address. So each line is 4B. So we have to insert 128 (512/2) line number of 0s. Please make it sure there is a “carriage-return” at the end of the file. The last line won’t get read. An easy debug option is put dummy instructions just like the current examples file contain them (00000004 00000008 0000000a 00000010 00000014)

(Q) I’m not sure how to understand Part-2 test code.

(A) The test in part-2 is modified code from RISC-V test suite. It uses macro function to generate test code.

(Q) How do I know what is the correct instruction/code behavior?

(A) you can probably use RISC-V interpreter or other RISC-V machine to execute the code. One example is here

(Q) How do I know whether I pass the code or not?

(A) For part-1, we provide test code. Your code should print out “Pass” message if you are using verilator.

(Q) My frame does not load any instruction. Do I need to change anything?

(A) The provided frame should load the first instruction correctly. If you don’t see any instruction, please check whether the contents of imem. With Verilator, FE_stage.v has the code to print out the imem contents.

FAQ for part-2

(Q) can I change the print messages of sim_main.cpp?

(A) yes you can add/change debug messages. but please do not change “` if(1 == exitcode)

std::cout&lt;&lt;“Passed!”&lt;&lt;std::endl; else std::cout&lt;&lt;“Failed. exitcode: “&lt;&lt;exitcode&lt;&lt;std::endl;

“`

(Q) what is li instructions in add.dump?

(A) li instruction is one of the pseudo instructions. It is the same as addi reg# x0, imm

(Q) I passed test[1-5].mem. why do I fail addi.mem ?

(A) RISC-V test suites test code all contain bne, auipc, jal instructions. So in order to pass RISC-V test suites, you need to complete those instructions.

(Q) I’d like to use RISC-V emulator for testing the test code. but it won’t take dump file. what should I do?

(A) Unfortunately RISC-V emulator does take only assembly instructions. Hence, we recommend to use another emulator . you can use *.dec file to copy and paste the contents.

(Q) Some tests code are long so we need to increase the simulation time. What should I do?

(A) in sim_main.cpp you can change #define RUN_CYCLES 15000 etc. as you need.

(Q) trace.vcd does not show the entire program execution. what should I do?

(A) please increase the number in prj-&gt;trace(trace, 2999); in sim_main.cpp We don’t want to put a high number since longer period means a longer file to work on. But if this cycle is not sufficient enough, you should increase it.

(Q) SED error in ./run_tests.sh

(A) Some Mac users have run into issues with the run_tests script. The error caused by sed sed: 1: ” …”: undefined label can be fixed by adding ‘.bak’ to the command in the makefile.Â Line 59 of the makefile should then look like thisÂ

sed -i ‘.bak’ $(SED_STRING) $(VX_DEFINE) If this continues to be an issue, please check out this post as it discusses different solutions for different MacOS versions.Â https://stackoverflow.com/questions/4247068/sed-command-with-i-option-failing-on-mac-but-works-on-linux

(Q) Behavior of lui . The documentation says that – Semantics : R[rd] = imm &lt;&lt; 12 But U-immediate already shifted the immediate by 12 bits. Do I need to shift the sxt_imm_DE. Do I need to shift immediate value again?

(A) No. if you have already shift immediage bits in instruction into sxt_imm_DE, you don’t have to shift sxt_imm_DE again.

(Q) bge is signed comparison and bgeu is unsigned comparison. What does it mean and what should I do?

(A) by default, in verilog all operations are unsigned. However, you can use signed comparisons in verilog by defining wires as signed variables.

Here is an example for signed comparisons and unsigned comparisons

“ wire signed [DBITS-1:0] s_regval1_AGEX; // note signed wire signed [`DBITS-1:0] s_regval2_AGEX; //note signed assign s_regval1_AGEX = regval1_AGEX; assign s_regval2_AGEX = regval2_AGEX;

// signed comparison wire s_less; assign s_less = (s_regval1_AGEX &lt; s_regval2_AGEX);

// unsigned comparison wire less; assign less = (regval1_AGEX &lt; regval2_AGEX); “`

Other methods are discussed here as well

(Q) bgeu and bltu use unsigned comparisons. Does it mean I shouldn’t sign extend immediage values at the decode stage and keep both unsiged and signed extension versions?

(A) No, in RISC-V, all immediate values are sign-extended. begu and bltu are unsigned comparisons with sing-extended values (e.g. sxt_imm_DE)

(Q) I’m still confused with signed keyword in verilog. Does it perform any sign conversion when I put signed keyword in the above example?

(A) In Verilog, values are just binary. s_regval1_AGEX and regval1_AGEX have the same value. Signed unsigned are just a matter of interpretation. When arithmetic operations are used such as comparator, signed/unsigned decide how to interpret the value. e.g.) In the above example, let’s assume that reval1_AGEX is 0x0000 and regval2_AGEX is 0xFFFF. In that case, s_regval1_AGEX is 0x0000 and s_regval2_AGEX is still 0xFFFF. However, s_regval2_AGEX is interpreted as -1 whereas regval2_AGEX is interpreted as 65535. Hence, if (regval1_AGEX &lt; regval2_AGEX) returns false but if (s_regval1_AGEX &lt; s_regval2_AGEX) returns true.

(Q) Do I need to put signed keyword for immediate values?

(A) Yes, even though immediate values are sign-extended, if we want to treat the immediate value as 2’s complement value such as in SLTI_I instruction case, you need to put signed keyword.

FAQ – part #3

(Q) Can you explain the behavior of slti and sltiu. Does it store the outcome of shift value?

(A) The outcome of both instructions should be either 0 or 1. It checks whether (R[rs1] &lt; sext(imm)) (signed comparisons for SLTI and unsigned comparisons for SLTIU) and if the condition is true, it sets 1 for the destination.

(Q) In tiny isa description, srai , srli and slli do not have immediate type. What should I do ?

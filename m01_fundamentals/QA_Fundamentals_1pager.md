# Module 1 — QA Fundamentals (1-pager)

1. Fundamentals of Testing

1.1. What is Testing?
"Software testing assesses software quality and helps reducing the risk of software failure in operation."

As in other industries material products need to be stressed physically (compressed, submerged, burned, accelerated, hit, etc), software needs to be tested in its ability to perform correctly.

Technical jargon:

Test object: A software subject to testing.
Verification: Checking wether a system meets specified requirements.
Validation: Checking whether the system meets users’ and other stakeholders’ 
needs in its operational environment.
Operational environment: The specific way the product is going to be used.
Dynamic testing: Involves the execution of software.
Static Testing: Doesn't involve the execution of the software.
Regression testing: Testing wether the debugging caused other defects in the test object.
Testing: Defect detection.
Debugging: Looking for the causes of the failure. This includes repeating the process which caused it, finding what went wrong, and fix it. 

What to look for in testing?
Verification and validation, specifically:
• Find defects by stressing the product to failure.
• Report to stakeholders to allow informed decisions. 


1.2. Why is Testing Necessary
"Testing, as a form of quality control, helps in achieving the agreed upon test objectives within the set scope, time, quality, and budget constraints."

Among other things, testing provides the POV of the user in the SDLC. The users ARE the ones who will have to deal with the product's defects. Testing, however, is cheaper to implement in the SDLC, than finding and paying for a representative user group. 

Though the manual isn't clear about the difference between testing and QA (Quality Assurance), it gestures towards the idea that QA involves testing + something else, making QA a more complete set of activities geared toward making a product ready for market. 

Technical jargon:
Error: A mistake committed by the user.
Defect: A mistake committed by the developer in the product.
Failure: The consequences of the defect while running the product. 

Meaning, defects eventually might cause failures. A defect is the cause, the failure is the effect. The defect will be some incorrect code; the failure, the sequence of unwanted computations that followed from it.   


1.3. Testing Principles

1. Testing is positive: It shows the presence not the absence of defects.
2. Testing can't be exhaustive: In practice is impossible to cover the whole program and, hence, testing tends to target priorities - things that can't really fail.
3. Test can save money: Better to prevent than to react.
4. Defects go together: Meaning most of the failures (problems) will have the same set of defects.  
5. Testing must be varied: Like antibiotics, too much of the same type of testing might lose its effectiveness.
6. Testing is contextual: Following from 5, one approach to testing wont solve everything. So testing must be context sensitive.
7. Testing doesn't ensure success: Even if 2 was false - meaning, every defect could be found and fixed - that wouldn't guarantee the success of the product. Namely the product meeting every expectation from its stakeholders and/or users. The mistakes might come from a previous other steps in the SDLC.

1.4. Test Activities, Testware and Test Roles


1.5. Essential Skills and Good Practices in Testing

# Translation of Z specifications to executable code: Application to the database domain

**Saeed Khalafinejad** $^{a,*}$, **Seyed-Hassan Mirian-Hosseinabadi** $^b$

$^a$ *School of Engineering and Science, Sharif University of Technology-International Campus, Kish Island, Iran*  
$^b$ *Department of Computer Engineering, Sharif University of Technology, Tehran, Iran*

---

### ABSTRACT

**Context:** It is well-known that the use of formal methods in the software development process results in high-quality software products. Having specified the software requirements in a formal notation, the question is how they can be transformed into an implementation. There is typically a mismatch between the specification and the implementation, known as the specification-implementation gap.  
**Objective:** This paper introduces a set of translation functions to fill the specification-implementation gap in the domain of database applications. We only present the formal definition, not the implementation, of the translation functions.  
**Method:** We chose Z, SQL and Delphi languages to illustrate our methodology. Because the mathematical foundation of Z has many properties in common with SQL, the translation functions from Z to SQL are derived easily. For the translation of Z to Delphi, we extend Delphi libraries to support Z mathematical structures such as sets and tuples. Then, based on these libraries, we derive the translation functions from Z to Delphi. Therefore, we establish a formal relationship between Z specifications and Delphi/SQL code. To prove the soundness of the translation from a Z abstract schema to the Delphi/SQL code, we define a Z design-level schema. We investigate the consistency of the Z abstract schema with the Z design-level schema by using Z refinement rules. Then, by the use of the laws of Morgan refinement calculus, we prove that the Delphi/SQL code refines the Z design-level schema.  
**Results:** The proposed approach can be used to build the correct prototype of a database application from its specification. This prototype can be evolved, or may be used to validate the software requirements specification against user requirements.  
**Conclusion:** Therefore, the work presented in this paper reduces the overall cost of the development of database applications because early validation reveals requirement errors sooner in the software development cycle.

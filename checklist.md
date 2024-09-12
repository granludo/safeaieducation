
DRAFT not for publication yet

# AI in Education Integration Checklist

This checklist is designed to guide the evaluation and integration of AI tools in educational settings, ensuring they align with the principles of the Safe AI in Education Manifesto.

This checklist is designed to be used by educators, technologists, and educational institutions to evaluate and integrate AI tools in education.

## 1 About the AI learning tool, its data and how it is processed  

###  Ownership and Control of Technology Stack of the AI Educational Tool

- **Does the institution own and control the entire technology stack of the AI Educational Tool?**
  - If the tool runs **on-premises** infrastructure, does the institution fully owns and manages all infrastructure and is responsible for maintaining compliance with privacy regulations (GDPR (Europe) and FERPA (USA)).?
- **If the tool runs fully or partialy on **cloud-based** infrastructure, the cloud provider:**
  - Is **Certified** for privacy and security compliance?.
  - Has clear **terms of service** that outline data protection responsibilities?
- **If the AI tool is provided **As a Service** (SaaS), the service vendor’s:**
  - Acredites **Certifications** for GDPR and FERPA compliance or the applicable privacy regulations?
  - Provides clearly defined **terms of service** that outline data usage, security measures, and responsibilities?
- **If the tool makes use of Generative AI models via API to AI vendors:**
  - Are all communication between the tool and the AI vendor encrypted?.  
  - Is it assured that no personal information is sent to AI Models?.
  - Acredites **Certifications** for GDPR and FERPA compliance or the applicable privacy regulations?
  - Do terms of service ensure that data shared with vendors will not be used for other purposes than the provision of the generative models?
  - There are clear **service-level agreements (SLAs)** or **terms of service** in place for vendor APIs, including compliance and QoS guarantees.
  - Are there clear policies for data retention, and can data be securely deleted upon request?

- [ ] **Ownership and Control of Data**  
  - [ ] The interactions of students with the AI Educational Tool are protected by the AI vendor's terms of service and service-level agreements (SLAs).
    - The educational institution retains full ownership and control of all personal student data?
    - If a third party AI vendor is used, are the student interactions with the AI Educational Tool protected by the AI vendor's terms of service and service-level agreements (SLAs)?
    - Are strict access controls in place to ensure only authorized personnel can access student data?
  - [ ] The educational institution is responsible and retains full ownership and control of student and teacher authentication and access to the tool.
    - The tool does not require students to register with external services.
  - [ ] Are student personal information and interactions with the tool encrypted both at rest and during transmission?
- [ ] **User Awareness of Data Processing**  
  - Does the interface clearly inform users about how their data is being processed and used?
  - If the tool gathers data from students, does it provide clear information about the types of data collected and how it will be used?
- [ ] **Research Use of Log Data**  
  - If the tool logs are to be used for research purposes, does it provide clear information about the types of data that will be logged and how it will be used?
  - Permission to use the log data for research purposes is obtained from the institution and the students.
- [ ] **Compliance with Privacy Laws**  
  - Does the tool comply with relevant data protection regulations (e.g., GDPR, FERPA)?
- [ ] **Data Minimization**  
  - Does the tool collect only the necessary data required for educational purposes?  
- [ ] **Data Retention and Deletion**  
  - Are there clear policies for data retention?
  - Can data be securely deleted upon request?

## About the Alignment with Educational Goals and Practices

- [ ] **Support for Learning Objectives**  
  - Does the AI tool directly support the institution’s specific learning objectives and educational outcomes?
- [ ] **Design for Educational Contexts**  
  - Is the tool specifically designed for educational use, aligning with established teaching methodologies and didactic models?
- [ ] **Control and alignment of AI models**
  - If generative AI models are used:
    - [ ] Is the original training dataset known and transparent?
    - [ ] Can the educational institution control the alignment and the parameters of the AI models?
      - [ ] Yes, the AI models used by the tool can be fine-tuned with custom data, knowledge and educational resources of the institution.
      - [ ] Yes, the tool allows for the integration of custom data, knowledge and educational resources of the institution in practices like prompt engineering, retrieval augmented genration(RAG) and other techniques using resources under the control of the institution.
- [ ] **Disclosure of content generated by AI**
  - Does the tool make it clear for students and teachers what content is generated by AI.
  - Are strategies for signaling that generated content is AI-generated, like digital watermarking or other techniques, implemented?
- [ ] **Explainability**
- Does the tool provide sources of information used to generate content?
- Are this sources of information made available to educators and students for verification and study?

## About Ai ethics and alignment

- [ ] **Ethical Training of AI**  
  - Was the AI model trained ethically, with transparency about the sources of training data and methodologies used?
- [ ] **Bias Minimization**  
  - Has the tool taken steps to identify and minimize biases in its training and outputs?
- [ ] **Vendor's Ethical Commitment**  
  - Does the vendor, or open source community, demonstrate a commitment to ethical AI development, specially in education?
- [ ] **Transparency of Limitations**  
  - Are users informed about the limitations of the AI tool based on its training data and design?
- [ ] **Disclosure of Potential Biases**  
  - Does the tool clearly indicate when outputs might be limited or biased due to gaps in training data?

## 6. Integration and Compatibility

- [ ] **Compatibility with Existing Systems**  
  - Is the AI tool compatible with the institution’s existing technology infrastructure (e.g., LMS, educational software)?
- [ ] **Technology Stack Integration**  
  - Can the tool be fully integrated into the institution's technology stack without reliance on external infrastructure?
- [ ] **Scalability**  
  - Can the tool scale to accommodate different class sizes, courses, and institutional needs?

## 7. Human Oversight and Accountability

- [ ] **Human Oversight**
  - Does the tool allow for human oversight of AI-driven decisions?
- [ ] **Appeal Process**
  - Is there a clear process for students to appeal AI-driven decisions through human-led processes?

## 8. Support and Training

- [ ] **Vendor Support**  
  - Does the vendor provide sufficient training and support for educators and IT staff?
- [ ] **Feedback Mechanisms**  
  - Does the tool provide ways for users to give feedback or report issues?
- [ ] **Ongoing Updates and Ethical Compliance**  
  - Is there ongoing monitoring and updating to ensure continued ethical compliance and performance?
- [ ] **Documentation and Resources**
  - Are comprehensive documentation and resources available for educators to understand how to effectively and ethically use the tool in their teaching?

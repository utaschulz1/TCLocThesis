# Appendix A Interviews

## Items and Answers

Apart from contact questions, I asked 7 open and 10 closed questions:

1. **Q4** What is your job in your company?

The interviewees had the following functions in their respective companies:
Solutions Architect, Business Development, CEO (2), Sales (2), Customer Success Manager, Consultant (4), Account Manager (2), Product Manager

2. **Q5** There is a ready-made version of the software that clients can use out-of-the-box with some configurations. Yes/No

This question targets the assumption that one type of portal can serve a multitude of users, data sources and use cases, while customization does not go further than configuration. User experience can be different in different user groups. If there is a relationship between the user experience and the content creation this had to be addressed for the different user groups in one out-of-the-box portal.

All 7 software producers have an out-of-the-box solution, or are developing one.

3. **Q6** What are the main reasons of your clients to start a documentation portal project? (multiple selection)\*
            A = self-help portal for product end-users
            B = documentation portal for in-company use
            C = documentation portal for internal and external use

This question targets the number and variety of use cases of documentation portals.

4 => self-help portal for product end-users
2 => documentation portal for in-company use
10 => documentation portal for internal and external use

2. **Q7** What other main reasons do companies have to for starting a documentation portal project? (open question)
   
This question targets the goals of documentation portals in terms of content and users.

3 => pull together information from several user groups
2 => digital transformation
2 => topic oriented information provision
2 => single point of truth
1 => feed information back into the system for quality improvement
2 => integration of other systems
1 => automated content delivery
1 => commercialize information
1 => trainings
1 => data service

3. **Q8-Q10** 3 Questions: Give an estimate how many out of 10 documentation portal buyers use the portal for 1/2/3 specific user groups.

3 questions to inquire how many different user groups these portals might serve:
 
![Qu8-Q10.png](../img/Qu8-Q10.png)

4. **Q11** More ideas about user groups for documentation portal projects?

The questions about user groups could reveal relations between users and content or system design.
   
5 => many user groups is the purpose of the system
1 => people use portals differently
1 => output in the portal differs according to logged-in user
2 => clients don't know their user groups exactly from start

5. **Q12** What sets of search facets are displayed in a documentation portal depends on the user group.

Strongly agree - Agree - Neither agree nor disagree - Disagree - Strongly disagree
This question targets the relation between facets in the portal UI and users.

![Q12.png](../img/Q12.png)

6. **Q13** How helpful is faceted search for users who don't know exactly what they are looking for?

Extremely helpful - Very helpful - Somewhat helpful - Not so helpful - Not at all helpful
This question targets the relation between facets and UX in portals.

![Q13.png](../img/Q13.png)

7.  **Q14** Give an estimate how many out of 10 documentation portal buyers could do with query search only, without faceted search?

This question targets the usability of facets as a specific means of user interaction in search.
Median = 0
7 said 0, 1 said 1, 1 said 2, 2 said 3, 1 said 7

8.  **Q15** What else can you tell me about how important facets are for certain user groups and how they are interdependent?

This question targets the existence of a relation between facets and users.

4 facets come from product
4 facets (should) come from users/use cases
5 facets come from CMS
2 facets are installed in an extra layer

9.  **Q16** For content to be safe, helpful and convenient it needs to appear with the right context. Which approach do you think is most effective to this end?

A = pre-assembled documents (MicroDocs, topics, chapters, manual...)
B = ontology
C = pre-assembled documents and ontology
D = both of the above combined with other technologies

This question targets the delivery of information units in their context, assuming that modularization and context are related. The question insinuates that context is related to UX.

![Q16.png](../img/Q16.png)

10. **Q17** Is there a knowledge graph involved in your system?

This question might serve for correlation.

Yes => 6
No  => 1

11. **Q18** More ideas about context approaches?

This question was supposed to reveal approaches and assumptions or viewpoints on delivering contextual information since the lack or abundance of information context can affect the user experience.

If not otherwise indicated by "(#)" it is one person per statement:

- People have learned to use documents that someone else has moderated for them
- When users collect their own books what happens with the safety information?
- One has to imagine the emotional state of such an end user. You want to fall back on well-known concepts.
- There has to be a way for users to make sure they are in the right places.

- Neighboring topics are also relevant.
- Topics are shown in the context of a manual
- Context is the responsibility of the content creator
- Ideally, topics describe all cases with sufficient context. BUT…

- For full-text search and metadata [from CCMS], first step: "What questions do the users have?"
- Set up your own graph-based navigation structure based on task/use case/product/product family
- individual searches represented by different navigation structures
- grouped search queries according to use case
- additionally separate layer via metadata
- There has to be a way for users to make sure they are in the right places. (repeated in this group)

- MicroDocs come from the info model of the ontology.
- Building ontologies requires a high effort
- Missing context was the trigger for developing the knowledge graph based CCMS in the beginning

1.  **Q19** How does the module size/granularity of content relate to user needs?

Targets the viewpoint of interviewees on the relation between user and modularity of content.
    
If not otherwise indicated by "(#)" it is one person per statement:

- User needs connect back to module size/granularity of content.
- The accepted text unit is … well as far as possible graphical. Users prefer videos, because they are shorter.
- There are different modules depending on the target group. This is independent of the CDP. So, regardless of whether this target group gets the content from the CDP or from somewhere else.
- Modularization depends on the target group.
- To begin with, one question should be answered with an answer from the CMS [means one module]. This also for the sake of usability.

- Content does not necessarily need to be modular according to the user. This can also be solved by recommendation in search.
- Using the modularization of the content in the documentation portal is not a priority.

- When modularizing, consider content creation vs. content production, e.g., mark content at sentence level, but then "cut" it according to user group during production. -> modularization on creation might serve different purpose than on production

- If the CDP requires smaller modules, this can be done using metadata or sematic technologies

- (2) One question is answered with one module.

- The technical writer defines the user groups for the text and creates content for different groups.
- To begin with, one question should be answered with an answer from the CMS [means one module.

1.  **Q20** In how far are usability tests of the portal done?

This question targets the relation between UX and content in documentation portals.

If not otherwise indicated by "(#)" it is one person per statement:

- I've never seen any user testing done
- not yet
- Usability falls by the wayside with these projects. Also because there are no experts.
- some clients do
- Proof of Concept
- Proof of Value
- We defined use cases by brainstorming and analyzing existing CMS content from clients.
- No, but there was this master student testing the system: 40% use faceted search to filter, 50% browse in the results.
- Usability tests are recommended to clients during the design phase
- we recommend clients to start with the user
- Clients can use Matomo
- The customer gets the system for 3 months to test. Then he can carry out usability tests himself and have the system adjusted.
- The clients do that, we are out of this
- Usability is the client's business.

### Interview Summary

**Out-of-the-box solutions**

All interviewed software producers had an out-of-the-box solution (or were building one). For different clients and content the portal would have a similar architecture of delivering content. This suggests that the user needs will be met by content characteristics. Out-of-the-box portal solutions typically provide findability supporting features like facets, navigation and query search. Facets as well as query search can retrieve information from content classes. Navigation is often based on content modules, see for example Bodrunova and Yakunin [-@BodrunovaYakunin2018]. The use of out-of-the-box solutions for portals is therefore a strong indicator that in such portals the user experience factors like findability or ease of use are related to classification and modularization of content.

**Many user groups**

5 of the interviewees said that having many user groups is the purpose of the documentation portal. All of them confirmed that portals actually have several user groups. Having content for several user groups delivered to one technical documentation portal implies that a solution for dealing with user-dependent relevance have to be implemented. In one interviewee's system this was solved by login. There are many solutions beyond login to deliver relevant content for a specific user group dynamically. User group information could be mapped to content classes in a certain layer or user groups could be implemented as metadata in the content. One interviewee stated that with only one user group the portal does not have any added value.

**Usability tests**

4 interviewees said that they never saw usability tests done and 4 said they do proof of value. 6 stated that usability tests are the responsibility of the buyer. This is an indication that documentation portals, for dedicated usability test, need real content. In other words, the user experience depends on the content, without being limited to this. This allows for the conclusion, that the content, its properties or the delivery process or combinations thereof are responsible for a part of the user experience in the documentation portal.

**Facets**

11 of 12 interviewees found facets to be important. 4 connected facets to products. Product classes are typically part of the content. 5 connected facets to users or use cases. 5 said facets come from the CCMS and 2 said that facets are installed in an extra layer.
Typically, role facets ("admin") and use cases in the form of life cycle information ("maintenance") are part of the content in the form of classes, attributes or metadata. However, user and use case could also refer to a login function or to aggregated content on delivery side ("onboarding") and would in this case be indirectly connected to content classes, for example, by use of an algorithm or mapping ("extra layer").
Hence the interviewees see a relation between content and facets in the documentation portal and consider facets to be important for the user.

**Information Context**

The interviewees related context to the user experience (findability, control, cognitive/emotional component), to modularization, to classification of content and to various possible technologies. I would like to cite 2 responses that show how user experience in content delivery requires a holistic view of the situation:

> "People have learned to use documents that someone else has moderated for them."

> "One has to imagine the emotional state of such an end user. You want to fall back on well-known concepts."

3 interviewees associated context with people's behavior, questioning the benefit of a pull approach with granular information for the user. 1 person, when ask about context, said that there has to be a way for users to make sure they are in the right places. Another associated context with MicroDocs coming from the information model of the ontology, which places use case dependent classification in a middle layer.

5 interviewees related information context to individualized search and had various specific solutions, such as pre-build queries represented by a facet, a QR code or any element. 1 interviewee considered navigation based on tasks, use cases, product family or product to represent context. Another representation was an additional user or use case dependent metadata layer. This relates metadata to user-based findability.

4 interviewees related context to neighbouring topics and considered technical writers to be responsible for context. This indicates a connection between content modularization on creation and the UX relevant aspect of context provision.

**Module Size**

Content is produced in information modules for the sake of reusability. I asked the interviewees how they relate module size to user needs. 5 interviewees related the module size or the modularization to user needs or said it to be user-dependent. 2 responded that one topic should answer one question (of the user). 2 interviewees said that module size in the CCMS is not necessarily related to user needs. These user needs in terms of module size can be addressed by recommendation in search, semantic technologies, or are not a priority at all, because modularization serves reuse on content production.

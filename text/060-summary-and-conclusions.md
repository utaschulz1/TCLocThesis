# Summary and Conclusion

Research about the relationship between UX in documentation portals and content creation is necessary since documentation portals have become mediators between content creators and users. Content classification and its use on delivery in applications is a common topic in information retrieval literature. However, there is a gap in the literature on research about UX and search in technical documentation portals and the connection to content creation, classification and modularization. The present thesis contributed by collecting experts' viewpoints on the topic, and by investigating possible characteristics and underlying principles of this relationship such as analytical measurements, relevance judgement or information scent. Also, how the relationship depends on different technologies was investigated.

## Touchpoints

1. Touchpoints from experts' point of view

| classes/modules        | element in documentation portal     | 
|--------------|-----------|
| role | login      | 
|--------------|-----------|
| various classes      | preassembled search queries  | 
|--------------|-----------|
| chapters, topics | tree-like side navigation | 
|--------------|-----------|
| metadata such as product model| facets/menus |

2. Measurable UX aspects of elements in IR applications that may be retrieved from classes and modules (selection)

|UX aspect|measurements|elements in UI| source |
|--------------|-----------|------------|----------|
|findability/subjective task difficulty | relevance judgment such as by topicality or reliability | tags in search results | @GwizdkaSpence2007, @Saracevic2019 |
|--------------|-----------|------------|----------|
|context provision/ subjective task difficulty |relevance judgment such as by specificity, amount, scope, depth of information | information module size | @GwizdkaSpence2007 |
|--------------|-----------|------------|----------|
|content relevance/accessibility | path analysis, order of navigational elements | navigation, menu | @DorfhuberZiegler2017ContentRelevanceAnalytics |
|--------------|-----------|------------|----------|
|findability | information scent | hierarchical menus | @Horiguchi2017 |
|--------------|-----------|------------|----------|
| findability/subjective task difficulty | optimal path length, complexity of navigational choices|navigational elements|@GwizdkaSpence2007|
|--------------|-----------|------------|----------|
|post-task perceived findability| search complexity, find time, number of pages visited | search, menu, side navigation, content hub| @GaoYu2020 |
|--------------|-----------|------------|----------|
|satisfaction|task complexity, perceived menu complexity|top menu, side navigation, popular links, content hub|@BodrunovaYakunin2018|
|--------------|-----------|------------|----------|
|helpfulness/findability| usability tests, UEQ | facets | @Hearst2018, @Gollub2019|


## Hypothesis and Findings

The present thesis could not prove the hypothesis to be true in general, however, the hypothesis is true under the condition that classification is directly leveraged for use in navigational and search elements in documentation portals. 


1. The relationship between classification and modularization of content and the user experience in documentation portals is typically mediated by use cases. In content delivery, use cases are technically expressed by semantic data structures and require classification. This classification can in some cases coincide with classification and modularization of content on creation.

2. Use cases can be implemented for content delivery with all technologies reviewed in this research, such as XSL transformations, semantic correlation layers or ontologies. In other words, a user-centered approach to content delivery can be realized independently of the technology used.

3. Classes and modules can be leveraged into the documentation portal directly without name change, aggregation or splitting, or indirectly via a use case based classification middle layer. 
Use case classification and content classification need to cooperate in that use case relevant information must be made explicit by tagging the content with respective classes. This can happen on content creation or in other processes.

Hence, a relationship between classification on content creation and UX aspects in documentation portals exists, but only when content classes are directly leveraged into the portal without being moderated by a use case. This conventional content-centered method of delivery is one of the methods currently in use. 

4. Facets typically originate directly from metadata of a document set. However, the way facets are implemented can have a strong impact on the user experience in documentation portals. This is backed by research evaluating two different facet implementations using the UEQ survey [@Gollub2019] and by usability tests of design variations [@Hearst2018]. Hence, the classes that facets render share their impact on UX aspects in documentation portals with the design of the facet implementation.


5. Experts found facets in technical documentation portals to be important for users. Some experts promoted a holistic view of users with their habits and context. 
This is in line with a context-sensitive approach based on script and prototype theory. Script and prototype theory can be used to inform use case creation methods that take the user context into account, not only on a situational and behavioral level, but also on a lexical level to inform facets and navigational elements.

6. Information scent can predict and simulate unlearned users' search behavior in hierarchical menus and be used to find pain points. Information scent can be seen as a characteristic of the underlying classification of a hierarchical menu. Such a menu may have its origin in a use case based structure or come directly from content classes. On the contrary, analytical measurements such as optimal path length, find time and others could not be clarified as characteristic for a relationship between classification and modularization of content and UX aspects in documentation portals. They can help to find pain points in UI elements, but do not reveal how they are related to content classification. 

7. When use cases moderate the user experience, there is no direct relationship between classification and modularization of content on creation and UX aspects in documentation portals. This is in line with the notion of aboutness underlying any classification on the one hand, and the notion of relevance underlying information retrieval on the other hand.

# coling-metaphors

## COLING 2020: Designing Meaning Representations workshop

## Annotation guidelines for DMR 2020 annotation exercise

1) Event Domain: 

The Event domain refers to the semantic domain in which an event takes place. The examples in this dataset contain verbs from physical and social domains; however, you cannot solely rely on the semantics of the verb to annotate the 'Event Domain'. All the physical verb-types in this dataset (i.e. Mereology, Motion, and Force) may occur in a Physical or Social 'event domain''. 

Physical Mereological verbs such as take can describe a Physical domain example She took the pillow from the bed or a Social Possession example She took the money from her boss.

Physical Motion verbs such as send or throw can describe a Physical domain example She threw a ball to the garden or a Social Possession example in the double object 'Transfer' ASC (e.g. She sent him a letter) or in a [Sbj V Obj to Obl] construction in which the to-oblique is a Recipient (e.g. She sent the letter to him). If the to-oblique is a Destination (i.e. physical Ground), the domain of the event should be annotated Physical:Motion; however, if the to-oblique is a Recipient, the domain of the event should be annotated Social:Possession.

Physical Force verbs such as grab can describe a Physical domain example She grabbed the fence or a Social domain example She grabbed the keys (and ran out the door). In the Physical example, the verb describes physical contact while in the Social example, the verb describes control of an object. 

Physical control of Possession does not need to be prolonged or permanent in order for the example to be identified as describing an event of Social:Possession. The control relation between the Possessor and the Possession may also not be physical. The Possession may be an inanimate object over which the Possessor has social or mental control (e.g. They stripped him of his title). 

The domain/subdomain usually can be determined by looking at the example and the types of participants that occur in the argument structure construction (ASC). However, you might come across examples that can be interpreted as both physical AND social at the same time. In such cases, you should annotate the domain as Social. 

Event Domain Annotation labels: 

Social:Possession
Physical:Mereology
Physical:Motion
Physical:Force


2) Force-dynamic (FD) Annotation labels:

The annotation of FD1 and FD2 force-dynamic labels should match the force-dynamic relations between participants in the argument structure construction (ASC). You will need to decide whether the verb is used in a metaphorical or non-metaphorical argument structure construction. If a Social or Physical verb is used in a metaphorical argument structure construction, the FD1 and FD2 annotation labels will match the 'source' (i.e. Physical) domain force-dynamic relations.  

FD1 labels are domain-INDEPENDENT. 

There are five FD1 annotation labels: 

Volitional
Self-volitional
Physical
Autonomous
Instrument

'Volitional' and 'Physical' FD1:

Volitional and Physical FD1 labels are used when the initiator of the causal chain is external to the 'core' event (e.g. in a metaphorical Remove ASC: She took the book from him or metaphorical Place ASC: She gave the book to him). Volition and Physical describe f-d relations between the initiator and another participant (usually one that undergoes some kind of change). The initiator of all the mereological ASCs is external. The initiator of the double object Transfer ASC (e.g. She passed him a book) is also external. If the external initiator is a volitional entity, the FD1 label should be 'Volitional.' If the initiator is not a volitional entity, the FD1 should be annotated 'Physical' (whether it is an actual physical entity or a non-physical entity).

'Self-volitional' and 'Autonomous' FD1:

Self-volitional and Autonomous is used when the initiator is not external to the core event, such as the Agent in physical or metaphorical Force ASCs (e.g. She hit the door or She got the book). Self-Volitional and Autonomous describe an internal process, or a lack of an external relation. If the initiator acts volitionally, the annotation label should be 'Self-volitional.' If the initiator is not a volitional entity, then the FD1 should be annotated 'Autonomous.'

'Instrument' FD1:

Instrument is used when an external initiator (i.e. Agent) manipulates an Instrument to carry out the action. The Instrument participant is usually realized as an antecedent with-oblique. The Instrument FD1 label describes the Agent + Instrument segment of the causal chain. You might encounter such examples with physical domain verbs, e.g. She hit him with a paddle or She cleaned the floor with an old mop. 

In many cases, there is a direct relation between the FD1 and FD2 labels. Some FD2 labels are not semantically compatible with certain FD1 labels. For example, the 'Force' FD2 label cannot be used with an external initiator. The initiator is always internal to the causal chain (i.e. Self-volitional or Autonomous FD1).

FD2 labels are domain-SPECIFIC.

FD2 label in a social domain ASC:

'Control' FD2: 

This FD2 label is used to describe the relation between the Possession and Possessor in Double Object ASCs, e.g. She gave him a book ('Volitional Control'). The first Object is always a Possessor, and the Double Object ASC is not used for physical events.


FD2 labels in physical domain ASCs:

Mereological ASCs:

Mereological ASCs occur with place and remove verbs in the physical domain. They can also be metaphorically extended to Possession and Transfer of Possession verbs in the social domain. There are four FD2 labels associated with the following ASCs:

'Place' [Sbj V Obj to/on Obl] (e.g. He gave the book to him)
'Remove' [Sbj V Obj from Obl] (e.g. She took the book from him) (Remove describes the (ablative) path relation between figure and ground.)
'Provide' [Sbj V Obj with Obl] (e.g. They presented him with a gift)
'Deprive' [Sbj V Obj of/ off of] (e.g. They stripped him off his title)

Force ASC:

The Force ASC is associated with Force and Constrain verbs in the physical domain. It can also be used metaphorically to describe Dynamic Possession events in the Transitive ASC (e.g. She got the book or She lost the book).

'Force' [Sbj V Obj] 

Motion ASCs:

The Motion ASC is associated with physical Motion verbs. In this dataset, it only includes verbs such as carry, send, throw, etc. The FD2 is annotated 'Motion' in the ASCs noted below:

'Motion' [Sbj V Obj PathP / Sbj V PathP]


ADDITIONAL DISCUSSION AND HELPFUL TIPS

Social:Possession verbs

There are two types of Social:Possession verbs: 'Dynamic Possession' and 'Transfer of Possession' verbs. 

Dynamic Possession verbs evoke an event structure with two participants: Possessor and Possession. These verbs describe events of 'obtaining/receiving' and 'losing/abandoning.' In a transitive ASC, Dynamic Possession verbs describe metaphorical Constrain (i.e. Force FD2). The FD1 annotation is Self-volitional (or Autonomous) in the transitive ASC because the Possessor is not an external initiator. In mereological ASCs, Dynamic Possession verbs describe metaphorical mereological events. The FD1 in mereological ASCs is always Volitional (or Physical) because the initiator is external to the 'core' event. Dynamic Possession verbs may describe obtaining or losing of Possession; however, the annotation of FD1 and FD2 does not distinguish the polarity of the verb. 

Transfer of Possession verbs evoke an event structure with three participants: Agent, Possession and Possessor. These verbs describe events of 'giving' and 'taking from/stealing'. Transfer of Possession verbs can occur in a Transitive ASC or metaphorical mereological ASCs. The causal chains for the Transitive ASC with these verbs always evokes a Null instantiated participant. For example, the annotation for She stole a purse needs to account for the Old Possessor (which is not syntactically expressed). Transitive examples with these verbs should be annotated Volitional Remove (or Volitional Place). 

You need to pay special attention to the context with these verbs to figure out whether you are annotating an ASC with a Dynamic Possession verb or a Transfer of Possession verb. This is particularly relevant when these verbs occur in the transitive ASC. The annotation of a transitive ASC with a Transfer of Possession verb is different from a Dynamic Possession verb. For example, verbs such as take can be Dynamic Possession verbs when an Original Possessor is not semantically evoked (e.g. She took the flower) but can also be Transfer of Possession verbs (e.g. She took his money).

Some things to consider when deciding whether an example includes an NI participant are: 

a) If an obtain verb is used in a stealing/illegal obtaining context, it is likely that it describes a Transfer of Possession event (e.g. She stole the money).
b) When an obtain verb occurs in a buying context, it describes a Transfer of Possession event (e.g. She bought a dress).
c) If the noun phrase that describes the Possession includes a possessive modifier (e.g. his money), that means there is an Original Possessor; the Original Possessor will be considered an NI argument of the verb.
d) If the direct object in the Transitive ASC with possession verbs is a Possessor (e.g. She robbed him), the Possession is always NI (i.e. Volitional Provide or Deprive).

You might be tempted to analyze certain obtain examples as 'Transfer of Possession' events (e.g. She accumulated a lot of books). However, unless an Original Possessor is clearly implied contextually, the annotation should not include it as an NI participant. The focus of the example above is on the Possessor OBTAINING books rather than 'taking them from someone.' If you are unsure whether an original Possessor (or Recipient with losing verbs) is part of the constructional semantics, then annotate the Transitive ASC as metaphorical Force.

Physical:Motion verbs

Motion verbs, e.g. send, throw, etc. can occur in a Motion or Double Object ASC. The Motion ASC expresses the Ground or the Recipient as a to-oblique, e.g. She threw a ball to him. The annotation for this example should be Volitional Motion. The Double Object ASC expresses both the Theme and the Recipient as direct objects, e.g. She threw him the ball and the annotation of this example should match the social Transfer ASC annotation labels, i.e. Volitional Control. 

Motion verbs can also occur in ASCs with NI participants, e.g. She sent him an email or She threw a rock. In order to decide whether the example describes a Transfer of Possession event or a Motion event, you will need to consider the type of participant in the direct object position. If the direct object is an entity that is meant to be received (e.g. an email or a letter), the example should be analyzed as describing a social event. As mentioned above, the social aspect of the event with Motion verbs will be annotated in the 'verb semantic domain' field. If it's possible for the event to be interpreted as both physical Motion AND social Transfer, the domain of the verb should be annotated Social.

Physical:Mereological verbs

Mereological verbs can occur in four different ASCs depending on the polarity of the verb and whether the Theme or the Ground is construed as the incremental theme (see above). If the Ground is not syntactically expressed with mereological verbs, it should be annotated as an NI participant (e.g. She poured water should be annotated Volitional Place).

The verb take can be used in a physical remove construal (e.g. She took the book off the shelf) or a constrain construal (annotated as 'Force FD2') in examples when an object is being used as an instrument, e.g. We took the cup and made it into a pot, or when the physical event does not evoke a Ground (e.g. She took the meal and left).

PASSIVE ASCs: Annotate Passive ASCs as though the event was in active voice. For example, She was given a book by her dad should be annotated Volitional Control (active voice: Her dad gave her a book).

ANNOTATION EXAMPLES WITH GETTING VERBS

Example 1:

Example: She received a book from him.
Event domain: Social: Possession
ASC form: [Sbj V Obj from Obl]
(ASC semantic domain: Physical: Mereological; NOT annotated but helps with the correct annotation of FD labels)
FD1 Annotation: Volitional
FD2 Annotation: Remove

Example 2:

Example: She found a book.
Event domain: Social: Possession
ASC form: [Sbj V Obj]
(ASC semantic domain: Physical: Force; NOT annotated but helps with the correct annotation of FD labels)
FD1 Annotation: Self-Volitional
FD2 Annotation: Force

ANNOTATION EXAMPLES WITH LOSING VERBS

Example 3:

Example: She lost a book.
Event domain: Social: Possession
ASC form: [Sbj V Obj]
(ASC semantic domain: Physical: Force; NOT annotated but helps with the correct annotation of FD labels)
FD1 Annotation: Self-Volitional
FD2 Annotation: Force

ANNOTATION EXAMPLES WITH GIVING VERBS

Example 4: 

Example: She gave him a book.
Event domain: Social: Possession
ASC form: [Sbj V Obj Obj]
(ASC semantic domain: Social: Possession; NOT annotated but helps with the correct annotation of FD labels)
FD1 Annotation: Volitional
FD2 Annotation: Control

Example 5: 

Example: She gave a book to the library.
Event domain: Social: Possession
ASC form: [Sbj V Obj Obj]
(ASC semantic domain: Physical: Mereological; NOT annotated but helps with the correct annotation of FD labels)
FD1 Annotation: Volitional
FD2 Annotation: Place

ANNOTATION EXAMPLES WITH STEALING VERBS

Example 6:

Example: She stole the book from him.
Event domain: Social: Possession
ASC form: [Sbj V Obj from Obl]
(ASC semantic domain: Physical: Mereological; NOT annotated but helps with the correct annotation of FD labels)
FD1 Annotation: Volitional
FD2 Annotation: Remove

ANNOTATION EXAMPLES WITH SEND/THROW VERBS

Example 7:

Example: She threw him a book.
Event domain: Social:Possession
ASC form: [Sbj V Obj Obj]
(ASC semantic domain: Social: Possession; NOT annotated but helps with the correct annotation of FD labels)
FD1 Annotation: Volitional
FD2 Annotation: Control

Example 8:

Example: She threw the book to him.
Event domain: Social:Possession
ASC form: [Sbj V Obj Obj]
(ASC semantic domain: Physical: Motion; NOT annotated but helps with the correct annotation of FD labels)
FD1 Annotation: Volitional
FD2 Annotation: Motion







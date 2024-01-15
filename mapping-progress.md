# Mapping Progress

Not all BBO classes are present in the mapping ([`rml-bpmn-to-bbo.ttl`](rml-bpmn-to-bbo.ttl)) yet. The following table gives an overview of the yet to be and already mapped classes, as well as which BPMN element(s) map(s) to which BBO class. When expanding the mapping, please also update the table.

Some classes are not part of the _standard_ BBO but are part of the _BBO extension_ as proposed by [https://link.springer.com/chapter/10.1007/978-3-031-12423-5_3](https://link.springer.com/chapter/10.1007/978-3-031-12423-5_3).

Note: all BBO classes and their specifications can be found here: [https://www.irit.fr/recherches/MELODI/ontologies/BBO/index-en.html#classes-headline](https://www.irit.fr/recherches/MELODI/ontologies/BBO/index-en.html#classes-headline).

| Mapped | BBO (extension) class                   | BPMN element(s)                  | BBO extension |
| :----: | --------------------------------------- | -------------------------------- | :-----------: |
|        | Activity                                |                                  |               |
|        | AdHocSubProcess                         |                                  |               |
|        | Agent                                   |                                  |               |
|        | AllMultiInstanceLoopCharacteristics     |                                  |               |
|   ✅   | Association                             | association                      |      ✅       |
|   ✅   | BoundaryEvent                           | boundaryEvent                    |               |
|   ✅   | BusinessRuleTask                        | businessRuleTask                 |               |
|        | CallableElement                         |                                  |               |
|        | CallActivity                            |                                  |               |
|        | CancelEvent                             |                                  |               |
|        | CancelEventDefinition                   |                                  |               |
|        | CatchEvent                              |                                  |               |
|        | Cell                                    |                                  |               |
|   ✅   | Collaboration                           | collaboration                    |      ✅       |
|        | CompensateEventDefinition               |                                  |               |
|        | CompensationEvent                       |                                  |               |
|        | ComplexMultiInstanceLoopCharacteristics |                                  |               |
|        | ComplexBehaviorDefinition               |                                  |               |
|        | ComplexGateway                          |                                  |               |
|        | Component                               |                                  |               |
|        | Computer                                |                                  |               |
|        | ConditionalEvent                        |                                  |               |
|        | ConditionalSequenceFlow                 |                                  |               |
|        | ConditionalEventDefinition              |                                  |               |
|        | ConditionExpression                     |                                  |               |
|        | ConsumableResource                      |                                  |               |
|        | ConvergingGateway                       |                                  |               |
|        | Database                                |                                  |               |
|   ✅   | DataInputAssocation                     | dataInputAssocation              |      ✅       |
|   ✅   | DataObject                              | dataObject                       |      ✅       |
|   ✅   | DataObjectReference                     | dataObjectReference              |      ✅       |
|   ✅   | DataOutputAssociation                   | dataOutputAssociation            |      ✅       |
|        | DataResource                            |                                  |               |
|   ✅   | DataStoreReference                      | dataStoreReference               |      ✅       |
|        | DefaultSequenceFlow                     |                                  |               |
|        | Device                                  |                                  |               |
|        | DivergingGateway                        |                                  |               |
|        | DocumentResource                        |                                  |               |
|   ✅   | EndEvent                                | endEvent                         |               |
|        | Enterprise                              |                                  |               |
|        | EquipmentDraw                           |                                  |               |
|   ✅   | Error                                   | error                            |               |
|        | ErrorEvent                              |                                  |               |
|   ✅   | ErrorEventDefinition                    | errorEventDefinition             |               |
|        | Escalation                              |                                  |               |
|        | EscalationEvent                         |                                  |               |
|        | EscalationEventDefinition               |                                  |               |
|        | Event                                   |                                  |               |
|        | EventSubProcess                         |                                  |               |
|        | EventBasedGateway                       |                                  |               |
|        | EventDefinition                         |                                  |               |
|        | EventSubProcessStartEvent               |                                  |               |
|        | ExclusiveEventBasedGateway              |                                  |               |
|   ✅   | ExclusiveGateway                        | exclusiveGateway                 |               |
|        | ExecutableBusinessProcess               |                                  |               |
|        | ExecutableScript                        |                                  |               |
|        | Expression                              |                                  |               |
|        | Factory                                 |                                  |               |
|        | FlowElement                             |                                  |               |
|        | FlowElementsContainer                   |                                  |               |
|        | FlowNode                                |                                  |               |
|        | FormalExpression                        |                                  |               |
|        | Gateway                                 |                                  |               |
|        | GlobalBusinessRuleTask                  |                                  |               |
|        | GlobalManualTask                        |                                  |               |
|        | GlobalScriptTask                        |                                  |               |
|        | GlobalTask                              |                                  |               |
|        | GlobalUserTask                          |                                  |               |
|        | Group                                   |                                  |               |
|        | HumanResource                           |                                  |               |
|        | ImplicitThrowEvent                      |                                  |               |
|   ✅   | InclusiveGateway                        | inclusiveGateway                 |               |
|        | InputOutputBinding                      |                                  |               |
|        | InputOutputSpecification                |                                  |               |
|        | InputSet                                |                                  |               |
|        | Interface                               |                                  |               |
|        | IntermediateCatchEvent                  |                                  |               |
|        | IntermediateEvent                       |                                  |               |
|   ✅   | IntermediateThrowEvent                  | intermediateThrowEvent           |               |
|        | InterruptingBoundaryEvent               |                                  |               |
|        | InterruptingEventSubProcessStartEvent   |                                  |               |
|        | InterruptingEventSubProcessStartEvent   |                                  |               |
|        | Job                                     |                                  |               |
|   ✅   | Lane                                    | lane                             |      ✅       |
|   ✅   | LaneSet                                 | laneSet                          |      ✅       |
|        | LinkEvent                               |                                  |               |
|        | LinkEventDefinition                     |                                  |               |
|        | LoopCharacteristics                     |                                  |               |
|   ✅   | ManualTask                              | manualTask                       |               |
|        | ManufacturingFacility                   |                                  |               |
|        | MaterialResource                        |                                  |               |
|        | Message                                 |                                  |               |
|   ✅   | MessageEventDefinition                  | messageEventDefinition           |               |
|   ✅   | MessageFlow                             | messageFlow                      |      ✅       |
|        | MixedGateway                            |                                  |               |
|        | MultiInstanceLoopCharacteristics        |                                  |               |
|        | MultipleEvent                           |                                  |               |
|        | NonEventSubProcessStartEvent            |                                  |               |
|        | NonInterruptingBoundaryEvent            |                                  |               |
|        | NoneEvent                               |                                  |               |
|        | NoneMultiInstanceLoopCharacteristics    |                                  |               |
|        | NonExecutableBusinessProcess            |                                  |               |
|        | NormalSequenceFlow                      |                                  |               |
|        | OneMultiInstanceLoopCharacteristics     |                                  |               |
|        | Operation                               |                                  |               |
|        | OutputSet                               |                                  |               |
|        | ParallelEventBasedGateway               |                                  |               |
|        | ParallelAdHocSubProcess                 |                                  |               |
|   ✅   | ParallelGateway                         | parallelGateway                  |               |
|        | ParallelMultipleEvent                   |                                  |               |
|        | Parameter                               |                                  |               |
|        | ParameterExpectedValue                  |                                  |               |
|        | ParameterValue                          |                                  |               |
|        | ParameterValueBinding                   |                                  |               |
|   ✅   | Participant                             | participant                      |      ✅       |
|        | Person                                  |                                  |               |
|        | PrivateProcess                          |                                  |               |
|   ✅   | Process                                 | process                          |               |
|        | ProcessStartEvent                       |                                  |               |
|   ✅   | Property                                | property                         |               |
|        | PublicProcess                           |                                  |               |
|        | QualitativeParameter                    |                                  |               |
|        | QuantitativeParameter                   |                                  |               |
|   ✅   | ReceiveTask                             | receiveTask                      |               |
|        | Rendering                               |                                  |               |
|        | Resource                                |                                  |               |
|        | ResourceCollection                      |                                  |               |
|        | ResourceParameter                       |                                  |               |
|        | ResourceState                           |                                  |               |
|        | Role                                    |                                  |               |
|        | RootElement                             |                                  |               |
|        | Scheme                                  |                                  |               |
|   ✅   | ScriptTask                              | scriptTask                       |               |
|   ✅   | SendTask                                | sendTask                         |               |
|   ✅   | SequenceFlow                            | incoming, outgoing, sequenceFlow |               |
|        | SequentialAdHocSubProcess               |                                  |               |
|   ✅   | ServiceTask                             | serviceTask                      |               |
|        | Shop                                    |                                  |               |
|        | Signal                                  |                                  |               |
|        | SignalEvent                             |                                  |               |
|        | SignalEventDefinition                   |                                  |               |
|        | SoftwareResource                        |                                  |               |
|        | SparePart                               |                                  |               |
|        | StandardLoopCharacteristics             |                                  |               |
|   ✅   | StartEvent                              | startEvent                       |               |
|        | Station                                 |                                  |               |
|   ✅   | SubProcess                              | subProcess                       |               |
|        | SubProcessStartEvent                    |                                  |               |
|   ✅   | Task                                    | task                             |               |
|        | TechnicalDocument                       |                                  |               |
|        | Telecommand                             |                                  |               |
|        | TerminateEvent                          |                                  |               |
|        | TerminateEventDefinition                |                                  |               |
|   ✅   | TextAnnotation                          | textAnnotation                   |      ✅       |
|        | ThrowEvent                              |                                  |               |
|        | TimeExpression                          |                                  |               |
|        | TimerEvent                              |                                  |               |
|        | TimerEventDefinition                    |                                  |               |
|        | Tool                                    |                                  |               |
|        | Transaction                             |                                  |               |
|        | UnderspecifiedExpression                |                                  |               |
|        | UnitOfMeasure                           |                                  |               |
|        | UnspecifiedGateway                      |                                  |               |
|        | UserGuide                               |                                  |               |
|   ✅   | UserTask                                | userTask                         |               |
|        | WorkProduct                             |                                  |               |
|        | WorkProcedureDocument                   |

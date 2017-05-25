ReactJS and Redux Examples

Redux Guide
1. Add constans(actions types)
2. Add actions(they return object with types to reducers to be executed)
3. Add reducers(they execute actions based on types)

mapStateToProps(state) // Returns reducers objects
mapDispatchToProps(state) // Return actions to be used on some events

  // Param 1. Enables reducers output tu be used  // Param 2. Enables actions to be used in code
connect(mapStateToProps, {action1, action2, action3} || mapDispatchToProps)(Class Name);

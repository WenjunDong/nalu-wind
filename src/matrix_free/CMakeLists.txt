target_sources(nalu PRIVATE
   ${CMAKE_CURRENT_SOURCE_DIR}/Coefficients.C
   ${CMAKE_CURRENT_SOURCE_DIR}/ConductionDiagonal.C
   ${CMAKE_CURRENT_SOURCE_DIR}/ConductionFields.C
   ${CMAKE_CURRENT_SOURCE_DIR}/ConductionGatheredFieldManager.C
   ${CMAKE_CURRENT_SOURCE_DIR}/ConductionInterior.C
   ${CMAKE_CURRENT_SOURCE_DIR}/ConductionJacobiPreconditioner.C
   ${CMAKE_CURRENT_SOURCE_DIR}/ConductionOperator.C
   ${CMAKE_CURRENT_SOURCE_DIR}/ConductionSolutionUpdate.C
   ${CMAKE_CURRENT_SOURCE_DIR}/ConductionUpdate.C
   ${CMAKE_CURRENT_SOURCE_DIR}/GaussLegendreQuadratureRule.C
   ${CMAKE_CURRENT_SOURCE_DIR}/LinearExposedAreas.C
   ${CMAKE_CURRENT_SOURCE_DIR}/LinearDiffusionMetric.C
   ${CMAKE_CURRENT_SOURCE_DIR}/LinearVolume.C
   ${CMAKE_CURRENT_SOURCE_DIR}/LobattoQuadratureRule.C
   ${CMAKE_CURRENT_SOURCE_DIR}/MatrixFreeSolver.C
   ${CMAKE_CURRENT_SOURCE_DIR}/NodeOrderMap.C
   ${CMAKE_CURRENT_SOURCE_DIR}/ScalarDirichletBC.C
   ${CMAKE_CURRENT_SOURCE_DIR}/ScalarFluxBC.C
   ${CMAKE_CURRENT_SOURCE_DIR}/StkSimdConnectivityMap.C
   ${CMAKE_CURRENT_SOURCE_DIR}/StkSimdNodeConnectivityMap.C
   ${CMAKE_CURRENT_SOURCE_DIR}/StkSimdFaceConnectivityMap.C
   ${CMAKE_CURRENT_SOURCE_DIR}/StkSimdGatheredElementData.C
   ${CMAKE_CURRENT_SOURCE_DIR}/StkToTpetraComm.C
   ${CMAKE_CURRENT_SOURCE_DIR}/StkToTpetraLocalIndices.C
   ${CMAKE_CURRENT_SOURCE_DIR}/StkToTpetraMap.C
)

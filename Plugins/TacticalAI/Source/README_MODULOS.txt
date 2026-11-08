MÓDULOS C++ PREVISTOS
=====================

Public/Core: TacticalAIController.h, BotContext.h, BotIntent.h, BotTags.h
Public/Perception: BotPerceptionComponent.h, SightEvaluator.h, HearingModel.h
Public/Beliefs: BotBeliefComponent.h, ThreatBelief.h, SearchArea.h
Public/Brain: BotBrainComponent.h, BotLayer.h, BotBrainDefinition.h, BotBrainRegistry.h
Public/Layers: classes base e adaptadores para layers
Public/Tactics: CoverSubsystem.h, CoverPoint.h, TacticalNavFilter.h
Public/Squad: SquadSubsystem.h, Squad.h, SquadPlanner.h, TokenPool.h, BarkSystem.h
Public/Combat: BotCombatComponent.h, AimModel.h, WeaponHandling.h
Public/Data: BotProfile.h, DifficultyTier.h, TuningCurves.h
Public/Debug: DecisionTrace.h, GameplayDebuggerCategory_Bot.h

Private/ deve conter implementações .cpp por domínio, sem misturar responsabilidades.
Este diretório documental não contém ainda arquivos C++ compiláveis nem Build.cs/uplugin.

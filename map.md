```Component: ARM Compiler 5.06 update 4 (build 422) Tool: armlink [4d35d2]

==============================================================================

Section Cross References

    led.o(i.FlashLED) refers to led.o(i.LED_On) for LED_On
    led.o(i.FlashLED) refers to led.o(i.LED_Off) for LED_Off
    main.o(i.main) refers to led.o(i.InitLED) for InitLED
    main.o(i.main) refers to led.o(i.FlashLED) for FlashLED
    os_core.o(i.OSEventNameGet) refers to os_core.o(i.OS_StrLen) for OS_StrLen
    os_core.o(i.OSEventNameGet) refers to os_core.o(.data) for OSIntNesting
    os_core.o(i.OSEventNameSet) refers to os_core.o(.data) for OSIntNesting
    os_core.o(i.OSEventPendMulti) refers to os_core.o(i.OS_EventTaskWaitMulti) for OS_EventTaskWaitMulti
    os_core.o(i.OSEventPendMulti) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_core.o(i.OSEventPendMulti) refers to os_core.o(i.OS_EventTaskRemoveMulti) for OS_EventTaskRemoveMulti
    os_core.o(i.OSEventPendMulti) refers to os_core.o(.data) for OSIntNesting
    os_core.o(i.OSInit) refers to os_cpu_c.o(i.OSInitHookBegin) for OSInitHookBegin
    os_core.o(i.OSInit) refers to os_core.o(i.OS_InitMisc) for OS_InitMisc
    os_core.o(i.OSInit) refers to os_core.o(i.OS_InitRdyList) for OS_InitRdyList
    os_core.o(i.OSInit) refers to os_core.o(i.OS_InitTCBList) for OS_InitTCBList
    os_core.o(i.OSInit) refers to os_core.o(i.OS_InitEventList) for OS_InitEventList
    os_core.o(i.OSInit) refers to os_flag.o(i.OS_FlagInit) for OS_FlagInit
    os_core.o(i.OSInit) refers to os_mem.o(i.OS_MemInit) for OS_MemInit
    os_core.o(i.OSInit) refers to os_q.o(i.OS_QInit) for OS_QInit
    os_core.o(i.OSInit) refers to os_core.o(i.OS_InitTaskIdle) for OS_InitTaskIdle
    os_core.o(i.OSInit) refers to os_core.o(i.OS_InitTaskStat) for OS_InitTaskStat
    os_core.o(i.OSInit) refers to os_tmr.o(i.OSTmr_Init) for OSTmr_Init
    os_core.o(i.OSInit) refers to os_cpu_c.o(i.OSInitHookEnd) for OSInitHookEnd
    os_core.o(i.OSInit) refers to os_dbg_r.o(i.OSDebugInit) for OSDebugInit
    os_core.o(i.OSIntEnter) refers to os_core.o(.data) for OSRunning
    os_core.o(i.OSIntExit) refers to os_core.o(i.OS_SchedNew) for OS_SchedNew
    os_core.o(i.OSIntExit) refers to os_cpu_c.o(i.OSIntCtxSw) for OSIntCtxSw
    os_core.o(i.OSIntExit) refers to os_core.o(.data) for OSRunning
    os_core.o(i.OSIntExit) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_core.o(i.OSSchedLock) refers to os_core.o(.data) for OSRunning
    os_core.o(i.OSSchedUnlock) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_core.o(i.OSSchedUnlock) refers to os_core.o(.data) for OSRunning
    os_core.o(i.OSStart) refers to os_core.o(i.OS_SchedNew) for OS_SchedNew
    os_core.o(i.OSStart) refers to os_cpu_c.o(i.OSStartHighRdy) for OSStartHighRdy
    os_core.o(i.OSStart) refers to os_core.o(.data) for OSRunning
    os_core.o(i.OSStart) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_core.o(i.OSStatInit) refers to os_time.o(i.OSTimeDly) for OSTimeDly
    os_core.o(i.OSStatInit) refers to os_core.o(.data) for OSIdleCtr
    os_core.o(i.OSTimeTick) refers to os_cpu_c.o(i.OSTimeTickHook) for OSTimeTickHook
    os_core.o(i.OSTimeTick) refers to os_core.o(.data) for OSTime
    os_core.o(i.OS_EventTaskRdy) refers to os_core.o(i.OS_EventTaskRemove) for OS_EventTaskRemove
    os_core.o(i.OS_EventTaskRdy) refers to os_core.o(i.OS_EventTaskRemoveMulti) for OS_EventTaskRemoveMulti
    os_core.o(i.OS_EventTaskRdy) refers to os_core.o(.constdata) for OSUnMapTbl
    os_core.o(i.OS_EventTaskRdy) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_core.o(i.OS_EventTaskRdy) refers to os_core.o(.data) for OSRdyGrp
    os_core.o(i.OS_EventTaskWait) refers to os_core.o(.data) for OSTCBCur
    os_core.o(i.OS_EventTaskWaitMulti) refers to os_core.o(.data) for OSTCBCur
    os_core.o(i.OS_InitEventList) refers to os_core.o(i.OS_MemClr) for OS_MemClr
    os_core.o(i.OS_InitEventList) refers to os_core.o(.bss) for OSEventTbl
    os_core.o(i.OS_InitEventList) refers to os_core.o(.data) for OSEventFreeList
    os_core.o(i.OS_InitMisc) refers to os_core.o(.data) for OSTime
    os_core.o(i.OS_InitRdyList) refers to os_core.o(.data) for OSRdyGrp
    os_core.o(i.OS_InitTCBList) refers to os_core.o(i.OS_MemClr) for OS_MemClr
    os_core.o(i.OS_InitTCBList) refers to os_core.o(.bss) for OSTCBTbl
    os_core.o(i.OS_InitTCBList) refers to os_core.o(.data) for OSTCBList
    os_core.o(i.OS_InitTaskIdle) refers to os_task.o(i.OSTaskCreateExt) for OSTaskCreateExt
    os_core.o(i.OS_InitTaskIdle) refers to os_task.o(i.OSTaskNameSet) for OSTaskNameSet
    os_core.o(i.OS_InitTaskIdle) refers to os_core.o(.bss) for OSTaskIdleStk
    os_core.o(i.OS_InitTaskIdle) refers to os_core.o(i.OS_TaskIdle) for OS_TaskIdle
    os_core.o(i.OS_InitTaskStat) refers to os_task.o(i.OSTaskCreateExt) for OSTaskCreateExt
    os_core.o(i.OS_InitTaskStat) refers to os_task.o(i.OSTaskNameSet) for OSTaskNameSet
    os_core.o(i.OS_InitTaskStat) refers to os_core.o(.bss) for OSTaskStatStk
    os_core.o(i.OS_InitTaskStat) refers to os_core.o(i.OS_TaskStat) for OS_TaskStat
    os_core.o(i.OS_Sched) refers to os_core.o(i.OS_SchedNew) for OS_SchedNew
    os_core.o(i.OS_Sched) refers to os_cpu_c.o(i.OSCtxSw) for OSCtxSw
    os_core.o(i.OS_Sched) refers to os_core.o(.data) for OSIntNesting
    os_core.o(i.OS_Sched) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_core.o(i.OS_SchedNew) refers to os_core.o(.constdata) for OSUnMapTbl
    os_core.o(i.OS_SchedNew) refers to os_core.o(.data) for OSRdyGrp
    os_core.o(i.OS_TCBInit) refers to os_cpu_c.o(i.OSTCBInitHook) for OSTCBInitHook
    os_core.o(i.OS_TCBInit) refers to os_cpu_c.o(i.OSTaskCreateHook) for OSTaskCreateHook
    os_core.o(i.OS_TCBInit) refers to os_core.o(.data) for OSTCBFreeList
    os_core.o(i.OS_TCBInit) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_core.o(i.OS_TaskIdle) refers to os_cpu_c.o(i.OSTaskIdleHook) for OSTaskIdleHook
    os_core.o(i.OS_TaskIdle) refers to os_core.o(.data) for OSIdleCtr
    os_core.o(i.OS_TaskStat) refers to os_time.o(i.OSTimeDly) for OSTimeDly
    os_core.o(i.OS_TaskStat) refers to os_task.o(i.OSTaskSuspend) for OSTaskSuspend
    os_core.o(i.OS_TaskStat) refers to os_cpu_c.o(i.OSTaskStatHook) for OSTaskStatHook
    os_core.o(i.OS_TaskStat) refers to os_core.o(i.OS_TaskStatStkChk) for OS_TaskStatStkChk
    os_core.o(i.OS_TaskStat) refers to os_core.o(.data) for OSStatRdy
    os_core.o(i.OS_TaskStatStkChk) refers to os_task.o(i.OSTaskStkChk) for OSTaskStkChk
    os_core.o(i.OS_TaskStatStkChk) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_dbg_r.o(i.OSDebugInit) refers to os_dbg_r.o(.constdata) for OSDebugEn
    os_dbg_r.o(i.OSDebugInit) refers to os_core.o(.bss) for OSTmrTbl
    os_flag.o(i.OSFlagCreate) refers to os_core.o(.data) for OSIntNesting
    os_flag.o(i.OSFlagDel) refers to os_flag.o(i.OS_FlagTaskRdy) for OS_FlagTaskRdy
    os_flag.o(i.OSFlagDel) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_flag.o(i.OSFlagDel) refers to os_core.o(.data) for OSIntNesting
    os_flag.o(i.OSFlagNameGet) refers to os_core.o(i.OS_StrLen) for OS_StrLen
    os_flag.o(i.OSFlagNameGet) refers to os_core.o(.data) for OSIntNesting
    os_flag.o(i.OSFlagNameSet) refers to os_core.o(.data) for OSIntNesting
    os_flag.o(i.OSFlagPend) refers to os_flag.o(i.OS_FlagBlock) for OS_FlagBlock
    os_flag.o(i.OSFlagPend) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_flag.o(i.OSFlagPend) refers to os_flag.o(i.OS_FlagUnlink) for OS_FlagUnlink
    os_flag.o(i.OSFlagPend) refers to os_core.o(.data) for OSIntNesting
    os_flag.o(i.OSFlagPendGetFlagsRdy) refers to os_core.o(.data) for OSTCBCur
    os_flag.o(i.OSFlagPost) refers to os_flag.o(i.OS_FlagTaskRdy) for OS_FlagTaskRdy
    os_flag.o(i.OSFlagPost) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_flag.o(i.OS_FlagBlock) refers to os_core.o(.data) for OSTCBCur
    os_flag.o(i.OS_FlagInit) refers to os_core.o(i.OS_MemClr) for OS_MemClr
    os_flag.o(i.OS_FlagInit) refers to os_core.o(.bss) for OSFlagTbl
    os_flag.o(i.OS_FlagInit) refers to os_core.o(.data) for OSFlagFreeList
    os_flag.o(i.OS_FlagTaskRdy) refers to os_flag.o(i.OS_FlagUnlink) for OS_FlagUnlink
    os_flag.o(i.OS_FlagTaskRdy) refers to os_core.o(.data) for OSRdyGrp
    os_mbox.o(i.OSMboxCreate) refers to os_core.o(i.OS_EventWaitListInit) for OS_EventWaitListInit
    os_mbox.o(i.OSMboxCreate) refers to os_core.o(.data) for OSIntNesting
    os_mbox.o(i.OSMboxDel) refers to os_core.o(i.OS_EventTaskRdy) for OS_EventTaskRdy
    os_mbox.o(i.OSMboxDel) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_mbox.o(i.OSMboxDel) refers to os_core.o(.data) for OSIntNesting
    os_mbox.o(i.OSMboxPend) refers to os_core.o(i.OS_EventTaskWait) for OS_EventTaskWait
    os_mbox.o(i.OSMboxPend) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_mbox.o(i.OSMboxPend) refers to os_core.o(i.OS_EventTaskRemove) for OS_EventTaskRemove
    os_mbox.o(i.OSMboxPend) refers to os_core.o(.data) for OSIntNesting
    os_mbox.o(i.OSMboxPendAbort) refers to os_core.o(i.OS_EventTaskRdy) for OS_EventTaskRdy
    os_mbox.o(i.OSMboxPendAbort) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_mbox.o(i.OSMboxPost) refers to os_core.o(i.OS_EventTaskRdy) for OS_EventTaskRdy
    os_mbox.o(i.OSMboxPost) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_mbox.o(i.OSMboxPostOpt) refers to os_core.o(i.OS_EventTaskRdy) for OS_EventTaskRdy
    os_mbox.o(i.OSMboxPostOpt) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_mem.o(i.OSMemCreate) refers to os_core.o(.data) for OSMemFreeList
    os_mem.o(i.OSMemNameGet) refers to os_core.o(i.OS_StrLen) for OS_StrLen
    os_mem.o(i.OSMemNameGet) refers to os_core.o(.data) for OSIntNesting
    os_mem.o(i.OSMemNameSet) refers to os_core.o(.data) for OSIntNesting
    os_mem.o(i.OS_MemInit) refers to os_core.o(i.OS_MemClr) for OS_MemClr
    os_mem.o(i.OS_MemInit) refers to os_core.o(.bss) for OSMemTbl
    os_mem.o(i.OS_MemInit) refers to os_core.o(.data) for OSMemFreeList
    os_mutex.o(i.OSMutexAccept) refers to os_core.o(.data) for OSIntNesting
    os_mutex.o(i.OSMutexCreate) refers to os_core.o(i.OS_EventWaitListInit) for OS_EventWaitListInit
    os_mutex.o(i.OSMutexCreate) refers to os_core.o(.data) for OSIntNesting
    os_mutex.o(i.OSMutexCreate) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_mutex.o(i.OSMutexDel) refers to os_mutex.o(i.OSMutex_RdyAtPrio) for OSMutex_RdyAtPrio
    os_mutex.o(i.OSMutexDel) refers to os_core.o(i.OS_EventTaskRdy) for OS_EventTaskRdy
    os_mutex.o(i.OSMutexDel) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_mutex.o(i.OSMutexDel) refers to os_core.o(.data) for OSIntNesting
    os_mutex.o(i.OSMutexDel) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_mutex.o(i.OSMutexPend) refers to os_core.o(i.OS_EventTaskWait) for OS_EventTaskWait
    os_mutex.o(i.OSMutexPend) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_mutex.o(i.OSMutexPend) refers to os_core.o(i.OS_EventTaskRemove) for OS_EventTaskRemove
    os_mutex.o(i.OSMutexPend) refers to os_core.o(.data) for OSIntNesting
    os_mutex.o(i.OSMutexPend) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_mutex.o(i.OSMutexPost) refers to os_mutex.o(i.OSMutex_RdyAtPrio) for OSMutex_RdyAtPrio
    os_mutex.o(i.OSMutexPost) refers to os_core.o(i.OS_EventTaskRdy) for OS_EventTaskRdy
    os_mutex.o(i.OSMutexPost) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_mutex.o(i.OSMutexPost) refers to os_core.o(.data) for OSIntNesting
    os_mutex.o(i.OSMutexPost) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_mutex.o(i.OSMutexQuery) refers to os_core.o(.data) for OSIntNesting
    os_mutex.o(i.OSMutex_RdyAtPrio) refers to os_core.o(.data) for OSRdyTbl
    os_mutex.o(i.OSMutex_RdyAtPrio) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_q.o(i.OSQCreate) refers to os_core.o(i.OS_EventWaitListInit) for OS_EventWaitListInit
    os_q.o(i.OSQCreate) refers to os_core.o(.data) for OSIntNesting
    os_q.o(i.OSQDel) refers to os_core.o(i.OS_EventTaskRdy) for OS_EventTaskRdy
    os_q.o(i.OSQDel) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_q.o(i.OSQDel) refers to os_core.o(.data) for OSIntNesting
    os_q.o(i.OSQPend) refers to os_core.o(i.OS_EventTaskWait) for OS_EventTaskWait
    os_q.o(i.OSQPend) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_q.o(i.OSQPend) refers to os_core.o(i.OS_EventTaskRemove) for OS_EventTaskRemove
    os_q.o(i.OSQPend) refers to os_core.o(.data) for OSIntNesting
    os_q.o(i.OSQPendAbort) refers to os_core.o(i.OS_EventTaskRdy) for OS_EventTaskRdy
    os_q.o(i.OSQPendAbort) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_q.o(i.OSQPost) refers to os_core.o(i.OS_EventTaskRdy) for OS_EventTaskRdy
    os_q.o(i.OSQPost) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_q.o(i.OSQPostFront) refers to os_core.o(i.OS_EventTaskRdy) for OS_EventTaskRdy
    os_q.o(i.OSQPostFront) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_q.o(i.OSQPostOpt) refers to os_core.o(i.OS_EventTaskRdy) for OS_EventTaskRdy
    os_q.o(i.OSQPostOpt) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_q.o(i.OS_QInit) refers to os_core.o(i.OS_MemClr) for OS_MemClr
    os_q.o(i.OS_QInit) refers to os_core.o(.bss) for OSQTbl
    os_q.o(i.OS_QInit) refers to os_core.o(.data) for OSQFreeList
    os_sem.o(i.OSSemCreate) refers to os_core.o(i.OS_EventWaitListInit) for OS_EventWaitListInit
    os_sem.o(i.OSSemCreate) refers to os_core.o(.data) for OSIntNesting
    os_sem.o(i.OSSemDel) refers to os_core.o(i.OS_EventTaskRdy) for OS_EventTaskRdy
    os_sem.o(i.OSSemDel) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_sem.o(i.OSSemDel) refers to os_core.o(.data) for OSIntNesting
    os_sem.o(i.OSSemPend) refers to os_core.o(i.OS_EventTaskWait) for OS_EventTaskWait
    os_sem.o(i.OSSemPend) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_sem.o(i.OSSemPend) refers to os_core.o(i.OS_EventTaskRemove) for OS_EventTaskRemove
    os_sem.o(i.OSSemPend) refers to os_core.o(.data) for OSIntNesting
    os_sem.o(i.OSSemPendAbort) refers to os_core.o(i.OS_EventTaskRdy) for OS_EventTaskRdy
    os_sem.o(i.OSSemPendAbort) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_sem.o(i.OSSemPost) refers to os_core.o(i.OS_EventTaskRdy) for OS_EventTaskRdy
    os_sem.o(i.OSSemPost) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_task.o(i.OSTaskChangePrio) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_task.o(i.OSTaskChangePrio) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_task.o(i.OSTaskChangePrio) refers to os_core.o(.data) for OSTCBCur
    os_task.o(i.OSTaskCreate) refers to os_cpu_c.o(i.OSTaskStkInit) for OSTaskStkInit
    os_task.o(i.OSTaskCreate) refers to os_core.o(i.OS_TCBInit) for OS_TCBInit
    os_task.o(i.OSTaskCreate) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_task.o(i.OSTaskCreate) refers to os_core.o(.data) for OSIntNesting
    os_task.o(i.OSTaskCreate) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_task.o(i.OSTaskCreateExt) refers to os_task.o(i.OS_TaskStkClr) for OS_TaskStkClr
    os_task.o(i.OSTaskCreateExt) refers to os_cpu_c.o(i.OSTaskStkInit) for OSTaskStkInit
    os_task.o(i.OSTaskCreateExt) refers to os_core.o(i.OS_TCBInit) for OS_TCBInit
    os_task.o(i.OSTaskCreateExt) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_task.o(i.OSTaskCreateExt) refers to os_core.o(.data) for OSIntNesting
    os_task.o(i.OSTaskCreateExt) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_task.o(i.OSTaskDel) refers to os_core.o(i.OS_EventTaskRemove) for OS_EventTaskRemove
    os_task.o(i.OSTaskDel) refers to os_core.o(i.OS_EventTaskRemoveMulti) for OS_EventTaskRemoveMulti
    os_task.o(i.OSTaskDel) refers to os_flag.o(i.OS_FlagUnlink) for OS_FlagUnlink
    os_task.o(i.OSTaskDel) refers to os_core.o(i.OS_Dummy) for OS_Dummy
    os_task.o(i.OSTaskDel) refers to os_cpu_c.o(i.OSTaskDelHook) for OSTaskDelHook
    os_task.o(i.OSTaskDel) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_task.o(i.OSTaskDel) refers to os_core.o(.data) for OSIntNesting
    os_task.o(i.OSTaskDel) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_task.o(i.OSTaskDelReq) refers to os_core.o(.data) for OSTCBCur
    os_task.o(i.OSTaskDelReq) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_task.o(i.OSTaskNameGet) refers to os_core.o(i.OS_StrLen) for OS_StrLen
    os_task.o(i.OSTaskNameGet) refers to os_core.o(.data) for OSIntNesting
    os_task.o(i.OSTaskNameGet) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_task.o(i.OSTaskNameSet) refers to os_core.o(.data) for OSIntNesting
    os_task.o(i.OSTaskNameSet) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_task.o(i.OSTaskQuery) refers to os_core.o(i.OS_MemCopy) for OS_MemCopy
    os_task.o(i.OSTaskQuery) refers to os_core.o(.data) for OSTCBCur
    os_task.o(i.OSTaskQuery) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_task.o(i.OSTaskRegGet) refers to os_core.o(.data) for OSTCBCur
    os_task.o(i.OSTaskRegGet) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_task.o(i.OSTaskRegGetID) refers to os_core.o(.data) for OSTaskRegNextAvailID
    os_task.o(i.OSTaskRegSet) refers to os_core.o(.data) for OSTCBCur
    os_task.o(i.OSTaskRegSet) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_task.o(i.OSTaskResume) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_task.o(i.OSTaskResume) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_task.o(i.OSTaskResume) refers to os_core.o(.data) for OSRdyGrp
    os_task.o(i.OSTaskStkChk) refers to os_core.o(.data) for OSTCBCur
    os_task.o(i.OSTaskStkChk) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_task.o(i.OSTaskSuspend) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_task.o(i.OSTaskSuspend) refers to os_core.o(.data) for OSTCBCur
    os_task.o(i.OSTaskSuspend) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_task.o(i.OS_TaskReturn) refers to os_cpu_c.o(i.OSTaskReturnHook) for OSTaskReturnHook
    os_task.o(i.OS_TaskReturn) refers to os_task.o(i.OSTaskDel) for OSTaskDel
    os_task.o(i.OS_TaskReturn) refers to os_core.o(.data) for OSTCBCur
    os_time.o(i.OSTimeDly) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_time.o(i.OSTimeDly) refers to os_core.o(.data) for OSIntNesting
    os_time.o(i.OSTimeDlyHMSM) refers to os_time.o(i.OSTimeDly) for OSTimeDly
    os_time.o(i.OSTimeDlyHMSM) refers to os_core.o(.data) for OSIntNesting
    os_time.o(i.OSTimeDlyResume) refers to os_core.o(i.OS_Sched) for OS_Sched
    os_time.o(i.OSTimeDlyResume) refers to os_core.o(.bss) for OSTCBPrioTbl
    os_time.o(i.OSTimeDlyResume) refers to os_core.o(.data) for OSRdyGrp
    os_time.o(i.OSTimeGet) refers to os_core.o(.data) for OSTime
    os_time.o(i.OSTimeSet) refers to os_core.o(.data) for OSTime
    os_tmr.o(i.OSTmrCreate) refers to os_core.o(i.OSSchedLock) for OSSchedLock
    os_tmr.o(i.OSTmrCreate) refers to os_tmr.o(i.OSTmr_Alloc) for OSTmr_Alloc
    os_tmr.o(i.OSTmrCreate) refers to os_core.o(i.OSSchedUnlock) for OSSchedUnlock
    os_tmr.o(i.OSTmrCreate) refers to os_core.o(.data) for OSIntNesting
    os_tmr.o(i.OSTmrDel) refers to os_core.o(i.OSSchedLock) for OSSchedLock
    os_tmr.o(i.OSTmrDel) refers to os_tmr.o(i.OSTmr_Unlink) for OSTmr_Unlink
    os_tmr.o(i.OSTmrDel) refers to os_tmr.o(i.OSTmr_Free) for OSTmr_Free
    os_tmr.o(i.OSTmrDel) refers to os_core.o(i.OSSchedUnlock) for OSSchedUnlock
    os_tmr.o(i.OSTmrDel) refers to os_core.o(.data) for OSIntNesting
    os_tmr.o(i.OSTmrNameGet) refers to os_core.o(i.OSSchedLock) for OSSchedLock
    os_tmr.o(i.OSTmrNameGet) refers to os_core.o(i.OS_StrLen) for OS_StrLen
    os_tmr.o(i.OSTmrNameGet) refers to os_core.o(i.OSSchedUnlock) for OSSchedUnlock
    os_tmr.o(i.OSTmrNameGet) refers to os_core.o(.data) for OSIntNesting
    os_tmr.o(i.OSTmrRemainGet) refers to os_core.o(i.OSSchedLock) for OSSchedLock
    os_tmr.o(i.OSTmrRemainGet) refers to os_core.o(i.OSSchedUnlock) for OSSchedUnlock
    os_tmr.o(i.OSTmrRemainGet) refers to os_core.o(.data) for OSIntNesting
    os_tmr.o(i.OSTmrSignal) refers to os_sem.o(i.OSSemPost) for OSSemPost
    os_tmr.o(i.OSTmrSignal) refers to os_core.o(.data) for OSTmrSemSignal
    os_tmr.o(i.OSTmrStart) refers to os_core.o(i.OSSchedLock) for OSSchedLock
    os_tmr.o(i.OSTmrStart) refers to os_tmr.o(i.OSTmr_Unlink) for OSTmr_Unlink
    os_tmr.o(i.OSTmrStart) refers to os_tmr.o(i.OSTmr_Link) for OSTmr_Link
    os_tmr.o(i.OSTmrStart) refers to os_core.o(i.OSSchedUnlock) for OSSchedUnlock
    os_tmr.o(i.OSTmrStart) refers to os_core.o(.data) for OSIntNesting
    os_tmr.o(i.OSTmrStateGet) refers to os_core.o(i.OSSchedLock) for OSSchedLock
    os_tmr.o(i.OSTmrStateGet) refers to os_core.o(i.OSSchedUnlock) for OSSchedUnlock
    os_tmr.o(i.OSTmrStateGet) refers to os_core.o(.data) for OSIntNesting
    os_tmr.o(i.OSTmrStop) refers to os_core.o(i.OSSchedLock) for OSSchedLock
    os_tmr.o(i.OSTmrStop) refers to os_tmr.o(i.OSTmr_Unlink) for OSTmr_Unlink
    os_tmr.o(i.OSTmrStop) refers to os_core.o(i.OSSchedUnlock) for OSSchedUnlock
    os_tmr.o(i.OSTmrStop) refers to os_core.o(.data) for OSIntNesting
    os_tmr.o(i.OSTmr_Alloc) refers to os_core.o(.data) for OSTmrFreeList
    os_tmr.o(i.OSTmr_Free) refers to os_core.o(.data) for OSTmrFreeList
    os_tmr.o(i.OSTmr_Init) refers to os_core.o(i.OS_MemClr) for OS_MemClr
    os_tmr.o(i.OSTmr_Init) refers to os_sem.o(i.OSSemCreate) for OSSemCreate
    os_tmr.o(i.OSTmr_Init) refers to os_core.o(i.OSEventNameSet) for OSEventNameSet
    os_tmr.o(i.OSTmr_Init) refers to os_tmr.o(i.OSTmr_InitTask) for OSTmr_InitTask
    os_tmr.o(i.OSTmr_Init) refers to os_core.o(.bss) for OSTmrTbl
    os_tmr.o(i.OSTmr_Init) refers to os_core.o(.data) for OSTmrTime
    os_tmr.o(i.OSTmr_InitTask) refers to os_task.o(i.OSTaskCreateExt) for OSTaskCreateExt
    os_tmr.o(i.OSTmr_InitTask) refers to os_task.o(i.OSTaskNameSet) for OSTaskNameSet
    os_tmr.o(i.OSTmr_InitTask) refers to os_core.o(.bss) for OSTmrTaskStk
    os_tmr.o(i.OSTmr_InitTask) refers to os_tmr.o(i.OSTmr_Task) for OSTmr_Task
    os_tmr.o(i.OSTmr_Link) refers to os_core.o(.data) for OSTmrTime
    os_tmr.o(i.OSTmr_Link) refers to os_core.o(.bss) for OSTmrWheelTbl
    os_tmr.o(i.OSTmr_Task) refers to os_sem.o(i.OSSemPend) for OSSemPend
    os_tmr.o(i.OSTmr_Task) refers to os_core.o(i.OSSchedLock) for OSSchedLock
    os_tmr.o(i.OSTmr_Task) refers to os_tmr.o(i.OSTmr_Unlink) for OSTmr_Unlink
    os_tmr.o(i.OSTmr_Task) refers to os_tmr.o(i.OSTmr_Link) for OSTmr_Link
    os_tmr.o(i.OSTmr_Task) refers to os_core.o(i.OSSchedUnlock) for OSSchedUnlock
    os_tmr.o(i.OSTmr_Task) refers to os_core.o(.data) for OSTmrSemSignal
    os_tmr.o(i.OSTmr_Task) refers to os_core.o(.bss) for OSTmrWheelTbl
    os_tmr.o(i.OSTmr_Unlink) refers to os_core.o(.bss) for OSTmrWheelTbl
    startup_stm32f401xe.o(STACK) refers (Special) to heapauxi.o(.text) for __use_two_region_memory
    startup_stm32f401xe.o(HEAP) refers (Special) to heapauxi.o(.text) for __use_two_region_memory
    startup_stm32f401xe.o(RESET) refers (Special) to heapauxi.o(.text) for __use_two_region_memory
    startup_stm32f401xe.o(RESET) refers to startup_stm32f401xe.o(STACK) for __initial_sp
    startup_stm32f401xe.o(RESET) refers to startup_stm32f401xe.o(.text) for Reset_Handler
    startup_stm32f401xe.o(.text) refers (Special) to heapauxi.o(.text) for __use_two_region_memory
    startup_stm32f401xe.o(.text) refers to system_stm32f4xx.o(i.SystemInit) for SystemInit
    startup_stm32f401xe.o(.text) refers to __main.o(!!!main) for __main
    startup_stm32f401xe.o(.text) refers to startup_stm32f401xe.o(HEAP) for Heap_Mem
    startup_stm32f401xe.o(.text) refers to startup_stm32f401xe.o(STACK) for Stack_Mem
    system_stm32f4xx.o(i.SystemCoreClockUpdate) refers to system_stm32f4xx.o(.data) for SystemCoreClock
    system_stm32f4xx.o(i.SystemCoreClockUpdate) refers to system_stm32f4xx.o(.constdata) for AHBPrescTable
    __main.o(!!!main) refers to __rtentry.o(.ARM.Collect$$rtentry$$00000000) for __rt_entry
    __rtentry.o(.ARM.Collect$$rtentry$$00000000) refers (Special) to __rtentry2.o(.ARM.Collect$$rtentry$$0000000A) for __rt_entry_li
    __rtentry.o(.ARM.Collect$$rtentry$$00000000) refers (Special) to __rtentry2.o(.ARM.Collect$$rtentry$$0000000D) for __rt_entry_main
    __rtentry.o(.ARM.Collect$$rtentry$$00000000) refers (Special) to __rtentry2.o(.ARM.Collect$$rtentry$$0000000C) for __rt_entry_postli_1
    __rtentry.o(.ARM.Collect$$rtentry$$00000000) refers (Special) to __rtentry2.o(.ARM.Collect$$rtentry$$00000009) for __rt_entry_postsh_1
    __rtentry.o(.ARM.Collect$$rtentry$$00000000) refers (Special) to __rtentry2.o(.ARM.Collect$$rtentry$$00000002) for __rt_entry_presh_1
    __rtentry.o(.ARM.Collect$$rtentry$$00000000) refers (Special) to __rtentry4.o(.ARM.Collect$$rtentry$$00000004) for __rt_entry_sh
    __rtentry2.o(.ARM.Collect$$rtentry$$00000008) refers to boardinit2.o(.text) for _platform_post_stackheap_init
    __rtentry2.o(.ARM.Collect$$rtentry$$0000000A) refers to libinit.o(.ARM.Collect$$libinit$$00000000) for __rt_lib_init
    __rtentry2.o(.ARM.Collect$$rtentry$$0000000B) refers to boardinit3.o(.text) for _platform_post_lib_init
    __rtentry2.o(.ARM.Collect$$rtentry$$0000000D) refers to main.o(i.main) for main
    __rtentry2.o(.ARM.Collect$$rtentry$$0000000D) refers to exit.o(.text) for exit
    __rtentry2.o(.ARM.exidx) refers to __rtentry2.o(.ARM.Collect$$rtentry$$00000001) for .ARM.Collect$$rtentry$$00000001
    __rtentry2.o(.ARM.exidx) refers to __rtentry2.o(.ARM.Collect$$rtentry$$00000008) for .ARM.Collect$$rtentry$$00000008
    __rtentry2.o(.ARM.exidx) refers to __rtentry2.o(.ARM.Collect$$rtentry$$0000000A) for .ARM.Collect$$rtentry$$0000000A
    __rtentry2.o(.ARM.exidx) refers to __rtentry2.o(.ARM.Collect$$rtentry$$0000000B) for .ARM.Collect$$rtentry$$0000000B
    __rtentry2.o(.ARM.exidx) refers to __rtentry2.o(.ARM.Collect$$rtentry$$0000000D) for .ARM.Collect$$rtentry$$0000000D
    __rtentry4.o(.ARM.Collect$$rtentry$$00000004) refers to sys_stackheap_outer.o(.text) for __user_setup_stackheap
    __rtentry4.o(.ARM.exidx) refers to __rtentry4.o(.ARM.Collect$$rtentry$$00000004) for .ARM.Collect$$rtentry$$00000004
    sys_stackheap_outer.o(.text) refers to libspace.o(.text) for __user_perproc_libspace
    sys_stackheap_outer.o(.text) refers to startup_stm32f401xe.o(.text) for __user_initial_stackheap
    exit.o(.text) refers to rtexit.o(.ARM.Collect$$rtexit$$00000000) for __rt_exit
    libinit.o(.ARM.Collect$$libinit$$00000000) refers (Special) to libinit2.o(.ARM.Collect$$libinit$$0000002E) for __rt_lib_init_alloca_1
    libinit.o(.ARM.Collect$$libinit$$00000000) refers (Special) to libinit2.o(.ARM.Collect$$libinit$$0000002C) for __rt_lib_init_argv_1
    libinit.o(.ARM.Collect$$libinit$$00000000) refers (Special) to libinit2.o(.ARM.Collect$$libinit$$0000001B) for __rt_lib_init_atexit_1
    libinit.o(.ARM.Collect$$libinit$$00000000) refers (Special) to libinit2.o(.ARM.Collect$$libinit$$00000021) for __rt_lib_init_clock_1
    libinit.o(.ARM.Collect$$libinit$$00000000) refers (Special) to libinit2.o(.ARM.Collect$$libinit$$00000032) for __rt_lib_init_cpp_1
    libinit.o(.ARM.Collect$$libinit$$00000000) refers (Special) to libinit2.o(.ARM.Collect$$libinit$$00000030) for __rt_lib_init_exceptions_1
    libinit.o(.ARM.Collect$$libinit$$00000000) refers (Special) to libinit2.o(.ARM.Collect$$libinit$$00000001) for __rt_lib_init_fp_1
    libinit.o(.ARM.Collect$$libinit$$00000000) refers (Special) to libinit2.o(.ARM.Collect$$libinit$$0000001F) for __rt_lib_init_fp_trap_1
    libinit.o(.ARM.Collect$$libinit$$00000000) refers (Special) to libinit2.o(.ARM.Collect$$libinit$$00000023) for __rt_lib_init_getenv_1
    libinit.o(.ARM.Collect$$libinit$$00000000) refers (Special) to libinit2.o(.ARM.Collect$$libinit$$0000000A) for __rt_lib_init_heap_1
    libinit.o(.ARM.Collect$$libinit$$00000000) refers (Special) to libinit2.o(.ARM.Collect$$libinit$$00000011) for __rt_lib_init_lc_collate_1
    libinit.o(.ARM.Collect$$libinit$$00000000) refers (Special) to libinit2.o(.ARM.Collect$$libinit$$00000013) for __rt_lib_init_lc_ctype_1
    libinit.o(.ARM.Collect$$libinit$$00000000) refers (Special) to libinit2.o(.ARM.Collect$$libinit$$00000015) for __rt_lib_init_lc_monetary_1
    libinit.o(.ARM.Collect$$libinit$$00000000) refers (Special) to libinit2.o(.ARM.Collect$$libinit$$00000017) for __rt_lib_init_lc_numeric_1
    libinit.o(.ARM.Collect$$libinit$$00000000) refers (Special) to libinit2.o(.ARM.Collect$$libinit$$00000019) for __rt_lib_init_lc_time_1
    libinit.o(.ARM.Collect$$libinit$$00000000) refers (Special) to libinit2.o(.ARM.Collect$$libinit$$00000004) for __rt_lib_init_preinit_1
    libinit.o(.ARM.Collect$$libinit$$00000000) refers (Special) to libinit2.o(.ARM.Collect$$libinit$$0000000E) for __rt_lib_init_rand_1
    libinit.o(.ARM.Collect$$libinit$$00000000) refers (Special) to libinit2.o(.ARM.Collect$$libinit$$00000033) for __rt_lib_init_return
    libinit.o(.ARM.Collect$$libinit$$00000000) refers (Special) to libinit2.o(.ARM.Collect$$libinit$$0000001D) for __rt_lib_init_signal_1
    libinit.o(.ARM.Collect$$libinit$$00000000) refers (Special) to libinit2.o(.ARM.Collect$$libinit$$00000025) for __rt_lib_init_stdio_1
    libinit.o(.ARM.Collect$$libinit$$00000000) refers (Special) to libinit2.o(.ARM.Collect$$libinit$$0000000C) for __rt_lib_init_user_alloc_1
    libspace.o(.text) refers to libspace.o(.bss) for __libspace_start
    rtexit.o(.ARM.Collect$$rtexit$$00000000) refers (Special) to rtexit2.o(.ARM.Collect$$rtexit$$00000004) for __rt_exit_exit
    rtexit.o(.ARM.Collect$$rtexit$$00000000) refers (Special) to rtexit2.o(.ARM.Collect$$rtexit$$00000003) for __rt_exit_ls
    rtexit.o(.ARM.Collect$$rtexit$$00000000) refers (Special) to rtexit2.o(.ARM.Collect$$rtexit$$00000002) for __rt_exit_prels_1
    rtexit.o(.ARM.exidx) refers (Special) to rtexit2.o(.ARM.Collect$$rtexit$$00000004) for __rt_exit_exit
    rtexit.o(.ARM.exidx) refers (Special) to rtexit2.o(.ARM.Collect$$rtexit$$00000003) for __rt_exit_ls
    rtexit.o(.ARM.exidx) refers (Special) to rtexit2.o(.ARM.Collect$$rtexit$$00000002) for __rt_exit_prels_1
    rtexit.o(.ARM.exidx) refers to rtexit.o(.ARM.Collect$$rtexit$$00000000) for .ARM.Collect$$rtexit$$00000000
    libinit2.o(.ARM.Collect$$libinit$$00000001) refers to fpinit.o(x$fpl$fpinit) for _fp_init
    libinit2.o(.ARM.Collect$$libinit$$00000010) refers to libinit2.o(.ARM.Collect$$libinit$$0000000F) for .ARM.Collect$$libinit$$0000000F
    libinit2.o(.ARM.Collect$$libinit$$00000012) refers to libinit2.o(.ARM.Collect$$libinit$$0000000F) for .ARM.Collect$$libinit$$0000000F
    libinit2.o(.ARM.Collect$$libinit$$00000014) refers to libinit2.o(.ARM.Collect$$libinit$$0000000F) for .ARM.Collect$$libinit$$0000000F
    libinit2.o(.ARM.Collect$$libinit$$00000016) refers to libinit2.o(.ARM.Collect$$libinit$$0000000F) for .ARM.Collect$$libinit$$0000000F
    libinit2.o(.ARM.Collect$$libinit$$00000018) refers to libinit2.o(.ARM.Collect$$libinit$$0000000F) for .ARM.Collect$$libinit$$0000000F
    libinit2.o(.ARM.Collect$$libinit$$00000026) refers to argv_veneer.o(.emb_text) for __ARM_argv_veneer
    libinit2.o(.ARM.Collect$$libinit$$00000027) refers to argv_veneer.o(.emb_text) for __ARM_argv_veneer
    rtexit2.o(.ARM.Collect$$rtexit$$00000003) refers to libshutdown.o(.ARM.Collect$$libshutdown$$00000000) for __rt_lib_shutdown
    rtexit2.o(.ARM.Collect$$rtexit$$00000004) refers to sys_exit.o(.text) for _sys_exit
    rtexit2.o(.ARM.exidx) refers to rtexit2.o(.ARM.Collect$$rtexit$$00000001) for .ARM.Collect$$rtexit$$00000001
    rtexit2.o(.ARM.exidx) refers to rtexit2.o(.ARM.Collect$$rtexit$$00000003) for .ARM.Collect$$rtexit$$00000003
    rtexit2.o(.ARM.exidx) refers to rtexit2.o(.ARM.Collect$$rtexit$$00000004) for .ARM.Collect$$rtexit$$00000004
    argv_veneer.o(.emb_text) refers to no_argv.o(.text) for __ARM_get_argv
    sys_exit.o(.text) refers (Special) to use_no_semi.o(.text) for __I$use$semihosting
    sys_exit.o(.text) refers (Special) to indicate_semi.o(.text) for __semihosting_library_function
    _get_argv_nomalloc.o(.text) refers (Special) to hrguard.o(.text) for __heap_region$guard
    _get_argv_nomalloc.o(.text) refers to defsig_rtmem_outer.o(.text) for __rt_SIGRTMEM
    _get_argv_nomalloc.o(.text) refers to sys_command.o(.text) for _sys_command_string
    libshutdown.o(.ARM.Collect$$libshutdown$$00000000) refers (Special) to libshutdown2.o(.ARM.Collect$$libshutdown$$00000002) for __rt_lib_shutdown_cpp_1
    libshutdown.o(.ARM.Collect$$libshutdown$$00000000) refers (Special) to libshutdown2.o(.ARM.Collect$$libshutdown$$00000007) for __rt_lib_shutdown_fp_trap_1
    libshutdown.o(.ARM.Collect$$libshutdown$$00000000) refers (Special) to libshutdown2.o(.ARM.Collect$$libshutdown$$0000000F) for __rt_lib_shutdown_heap_1
    libshutdown.o(.ARM.Collect$$libshutdown$$00000000) refers (Special) to libshutdown2.o(.ARM.Collect$$libshutdown$$00000010) for __rt_lib_shutdown_return
    libshutdown.o(.ARM.Collect$$libshutdown$$00000000) refers (Special) to libshutdown2.o(.ARM.Collect$$libshutdown$$0000000A) for __rt_lib_shutdown_signal_1
    libshutdown.o(.ARM.Collect$$libshutdown$$00000000) refers (Special) to libshutdown2.o(.ARM.Collect$$libshutdown$$00000004) for __rt_lib_shutdown_stdio_1
    libshutdown.o(.ARM.Collect$$libshutdown$$00000000) refers (Special) to libshutdown2.o(.ARM.Collect$$libshutdown$$0000000C) for __rt_lib_shutdown_user_alloc_1
    sys_command.o(.text) refers (Special) to use_no_semi.o(.text) for __I$use$semihosting
    sys_command.o(.text) refers (Special) to indicate_semi.o(.text) for __semihosting_library_function
    defsig_rtmem_outer.o(.text) refers to defsig_rtmem_inner.o(.text) for __rt_SIGRTMEM_inner
    defsig_rtmem_outer.o(.text) refers to defsig_exit.o(.text) for __sig_exit
    defsig_rtmem_formal.o(.text) refers to rt_raise.o(.text) for __rt_raise
    rt_raise.o(.text) refers to __raise.o(.text) for __raise
    rt_raise.o(.text) refers to sys_exit.o(.text) for _sys_exit
    defsig_exit.o(.text) refers to sys_exit.o(.text) for _sys_exit
    defsig_rtmem_inner.o(.text) refers to defsig_general.o(.text) for __default_signal_display
    __raise.o(.text) refers to defsig.o(CL$$defsig) for __default_signal_handler
    defsig_general.o(.text) refers to sys_wrch.o(.text) for _ttywrch
    sys_wrch.o(.text) refers (Special) to use_no_semi.o(.text) for __I$use$semihosting
    sys_wrch.o(.text) refers (Special) to indicate_semi.o(.text) for __semihosting_library_function
    defsig.o(CL$$defsig) refers to defsig_rtmem_inner.o(.text) for __rt_SIGRTMEM_inner
    defsig_abrt_inner.o(.text) refers to defsig_general.o(.text) for __default_signal_display
    defsig_fpe_inner.o(.text) refers to defsig_general.o(.text) for __default_signal_display
    defsig_rtred_inner.o(.text) refers to defsig_general.o(.text) for __default_signal_display
    defsig_stak_inner.o(.text) refers to defsig_general.o(.text) for __default_signal_display
    defsig_pvfn_inner.o(.text) refers to defsig_general.o(.text) for __default_signal_display
    defsig_cppl_inner.o(.text) refers to defsig_general.o(.text) for __default_signal_display
    defsig_segv_inner.o(.text) refers to defsig_general.o(.text) for __default_signal_display
    defsig_other.o(.text) refers to defsig_general.o(.text) for __default_signal_display


==============================================================================

Removing Unused input sections from the image.

    Removing led.o(.rev16_text), (4 bytes).
    Removing led.o(.revsh_text), (4 bytes).
    Removing led.o(.rrx_text), (6 bytes).
    Removing main.o(.rev16_text), (4 bytes).
    Removing main.o(.revsh_text), (4 bytes).
    Removing main.o(.rrx_text), (6 bytes).
    Removing os_core.o(i.OSEventNameGet), (116 bytes).
    Removing os_core.o(i.OSEventNameSet), (92 bytes).
    Removing os_core.o(i.OSEventPendMulti), (696 bytes).
    Removing os_core.o(i.OSInit), (56 bytes).
    Removing os_core.o(i.OSIntEnter), (36 bytes).
    Removing os_core.o(i.OSIntExit), (140 bytes).
    Removing os_core.o(i.OSSchedLock), (56 bytes).
    Removing os_core.o(i.OSSchedUnlock), (80 bytes).
    Removing os_core.o(i.OSStart), (72 bytes).
    Removing os_core.o(i.OSStatInit), (68 bytes).
    Removing os_core.o(i.OSTimeTick), (228 bytes).
    Removing os_core.o(i.OSVersion), (6 bytes).
    Removing os_core.o(i.OS_Dummy), (2 bytes).
    Removing os_core.o(i.OS_EventTaskRdy), (148 bytes).
    Removing os_core.o(i.OS_EventTaskRemove), (46 bytes).
    Removing os_core.o(i.OS_EventTaskRemoveMulti), (58 bytes).
    Removing os_core.o(i.OS_EventTaskWait), (124 bytes).
    Removing os_core.o(i.OS_EventTaskWaitMulti), (148 bytes).
    Removing os_core.o(i.OS_EventWaitListInit), (28 bytes).
    Removing os_core.o(i.OS_InitEventList), (96 bytes).
    Removing os_core.o(i.OS_InitMisc), (92 bytes).
    Removing os_core.o(i.OS_InitRdyList), (68 bytes).
    Removing os_core.o(i.OS_InitTCBList), (128 bytes).
    Removing os_core.o(i.OS_InitTaskIdle), (80 bytes).
    Removing os_core.o(i.OS_InitTaskStat), (80 bytes).
    Removing os_core.o(i.OS_MemClr), (18 bytes).
    Removing os_core.o(i.OS_MemCopy), (20 bytes).
    Removing os_core.o(i.OS_Sched), (112 bytes).
    Removing os_core.o(i.OS_SchedNew), (44 bytes).
    Removing os_core.o(i.OS_StrLen), (28 bytes).
    Removing os_core.o(i.OS_TCBInit), (308 bytes).
    Removing os_core.o(i.OS_TaskIdle), (32 bytes).
    Removing os_core.o(i.OS_TaskStat), (196 bytes).
    Removing os_core.o(i.OS_TaskStatStkChk), (60 bytes).
    Removing os_core.o(.bss), (5048 bytes).
    Removing os_core.o(.constdata), (256 bytes).
    Removing os_core.o(.data), (100 bytes).
    Removing os_dbg_r.o(i.OSDebugInit), (348 bytes).
    Removing os_dbg_r.o(.constdata), (118 bytes).
    Removing os_flag.o(i.OSFlagAccept), (218 bytes).
    Removing os_flag.o(i.OSFlagCreate), (88 bytes).
    Removing os_flag.o(i.OSFlagDel), (228 bytes).
    Removing os_flag.o(i.OSFlagNameGet), (100 bytes).
    Removing os_flag.o(i.OSFlagNameSet), (72 bytes).
    Removing os_flag.o(i.OSFlagPend), (580 bytes).
    Removing os_flag.o(i.OSFlagPendGetFlagsRdy), (24 bytes).
    Removing os_flag.o(i.OSFlagPost), (318 bytes).
    Removing os_flag.o(i.OSFlagQuery), (48 bytes).
    Removing os_flag.o(i.OS_FlagBlock), (164 bytes).
    Removing os_flag.o(i.OS_FlagInit), (88 bytes).
    Removing os_flag.o(i.OS_FlagTaskRdy), (96 bytes).
    Removing os_flag.o(i.OS_FlagUnlink), (36 bytes).
    Removing os_mbox.o(i.OSMboxAccept), (38 bytes).
    Removing os_mbox.o(i.OSMboxCreate), (80 bytes).
    Removing os_mbox.o(i.OSMboxDel), (224 bytes).
    Removing os_mbox.o(i.OSMboxPend), (268 bytes).
    Removing os_mbox.o(i.OSMboxPendAbort), (132 bytes).
    Removing os_mbox.o(i.OSMboxPost), (84 bytes).
    Removing os_mbox.o(i.OSMboxPostOpt), (124 bytes).
    Removing os_mbox.o(i.OSMboxQuery), (74 bytes).
    Removing os_mem.o(i.OSMemCreate), (156 bytes).
    Removing os_mem.o(i.OSMemGet), (60 bytes).
    Removing os_mem.o(i.OSMemNameGet), (80 bytes).
    Removing os_mem.o(i.OSMemNameSet), (56 bytes).
    Removing os_mem.o(i.OSMemPut), (58 bytes).
    Removing os_mem.o(i.OSMemQuery), (58 bytes).
    Removing os_mem.o(i.OS_MemInit), (88 bytes).
    Removing os_mutex.o(i.OSMutexAccept), (144 bytes).
    Removing os_mutex.o(i.OSMutexCreate), (172 bytes).
    Removing os_mutex.o(i.OSMutexDel), (308 bytes).
    Removing os_mutex.o(i.OSMutexPend), (592 bytes).
    Removing os_mutex.o(i.OSMutexPost), (204 bytes).
    Removing os_mutex.o(i.OSMutexQuery), (112 bytes).
    Removing os_mutex.o(i.OSMutex_RdyAtPrio), (132 bytes).
    Removing os_q.o(i.OSQAccept), (88 bytes).
    Removing os_q.o(i.OSQCreate), (152 bytes).
    Removing os_q.o(i.OSQDel), (260 bytes).
    Removing os_q.o(i.OSQFlush), (46 bytes).
    Removing os_q.o(i.OSQPend), (296 bytes).
    Removing os_q.o(i.OSQPendAbort), (132 bytes).
    Removing os_q.o(i.OSQPost), (112 bytes).
    Removing os_q.o(i.OSQPostFront), (114 bytes).
    Removing os_q.o(i.OSQPostOpt), (180 bytes).
    Removing os_q.o(i.OSQQuery), (98 bytes).
    Removing os_q.o(i.OS_QInit), (80 bytes).
    Removing os_sem.o(i.OSSemAccept), (42 bytes).
    Removing os_sem.o(i.OSSemCreate), (80 bytes).
    Removing os_sem.o(i.OSSemDel), (224 bytes).
    Removing os_sem.o(i.OSSemPend), (244 bytes).
    Removing os_sem.o(i.OSSemPendAbort), (132 bytes).
    Removing os_sem.o(i.OSSemPost), (86 bytes).
    Removing os_sem.o(i.OSSemQuery), (74 bytes).
    Removing os_sem.o(i.OSSemSet), (60 bytes).
    Removing os_task.o(i.OSTaskChangePrio), (428 bytes).
    Removing os_task.o(i.OSTaskCreate), (156 bytes).
    Removing os_task.o(i.OSTaskCreateExt), (176 bytes).
    Removing os_task.o(i.OSTaskDel), (352 bytes).
    Removing os_task.o(i.OSTaskDelReq), (104 bytes).
    Removing os_task.o(i.OSTaskNameGet), (144 bytes).
    Removing os_task.o(i.OSTaskNameSet), (116 bytes).
    Removing os_task.o(i.OSTaskQuery), (100 bytes).
    Removing os_task.o(i.OSTaskRegGet), (80 bytes).
    Removing os_task.o(i.OSTaskRegGetID), (56 bytes).
    Removing os_task.o(i.OSTaskRegSet), (76 bytes).
    Removing os_task.o(i.OSTaskResume), (168 bytes).
    Removing os_task.o(i.OSTaskStkChk), (132 bytes).
    Removing os_task.o(i.OSTaskSuspend), (180 bytes).
    Removing os_task.o(i.OS_TaskReturn), (24 bytes).
    Removing os_task.o(i.OS_TaskStkClr), (26 bytes).
    Removing os_time.o(i.OSTimeDly), (116 bytes).
    Removing os_time.o(i.OSTimeDlyHMSM), (132 bytes).
    Removing os_time.o(i.OSTimeDlyResume), (168 bytes).
    Removing os_time.o(i.OSTimeGet), (20 bytes).
    Removing os_time.o(i.OSTimeSet), (20 bytes).
    Removing os_tmr.o(i.OSTmrCreate), (164 bytes).
    Removing os_tmr.o(i.OSTmrDel), (140 bytes).
    Removing os_tmr.o(i.OSTmrNameGet), (140 bytes).
    Removing os_tmr.o(i.OSTmrRemainGet), (180 bytes).
    Removing os_tmr.o(i.OSTmrSignal), (20 bytes).
    Removing os_tmr.o(i.OSTmrStart), (144 bytes).
    Removing os_tmr.o(i.OSTmrStateGet), (100 bytes).
    Removing os_tmr.o(i.OSTmrStop), (196 bytes).
    Removing os_tmr.o(i.OSTmr_Alloc), (64 bytes).
    Removing os_tmr.o(i.OSTmr_Free), (76 bytes).
    Removing os_tmr.o(i.OSTmr_Init), (244 bytes).
    Removing os_tmr.o(i.OSTmr_InitTask), (80 bytes).
    Removing os_tmr.o(i.OSTmr_Link), (116 bytes).
    Removing os_tmr.o(i.OSTmr_Task), (132 bytes).
    Removing os_tmr.o(i.OSTmr_Unlink), (72 bytes).
    Removing app_hooks.o(i.App_TCBInitHook), (2 bytes).
    Removing app_hooks.o(i.App_TaskCreateHook), (2 bytes).
    Removing app_hooks.o(i.App_TaskDelHook), (2 bytes).
    Removing app_hooks.o(i.App_TaskIdleHook), (2 bytes).
    Removing app_hooks.o(i.App_TaskReturnHook), (2 bytes).
    Removing app_hooks.o(i.App_TaskStatHook), (2 bytes).
    Removing app_hooks.o(i.App_TaskSwHook), (2 bytes).
    Removing app_hooks.o(i.App_TimeTickHook), (2 bytes).
    Removing os_cpu_c.o(i.OSCtxSw), (2 bytes).
    Removing os_cpu_c.o(i.OSInitHookBegin), (2 bytes).
    Removing os_cpu_c.o(i.OSInitHookEnd), (2 bytes).
    Removing os_cpu_c.o(i.OSIntCtxSw), (2 bytes).
    Removing os_cpu_c.o(i.OSStartHighRdy), (2 bytes).
    Removing os_cpu_c.o(i.OSTCBInitHook), (2 bytes).
    Removing os_cpu_c.o(i.OSTaskCreateHook), (2 bytes).
    Removing os_cpu_c.o(i.OSTaskDelHook), (2 bytes).
    Removing os_cpu_c.o(i.OSTaskIdleHook), (2 bytes).
    Removing os_cpu_c.o(i.OSTaskReturnHook), (2 bytes).
    Removing os_cpu_c.o(i.OSTaskStatHook), (2 bytes).
    Removing os_cpu_c.o(i.OSTaskStkInit), (8 bytes).
    Removing os_cpu_c.o(i.OSTaskSwHook), (2 bytes).
    Removing os_cpu_c.o(i.OSTickISR), (2 bytes).
    Removing os_cpu_c.o(i.OSTimeTickHook), (2 bytes).
    Removing system_stm32f4xx.o(.rev16_text), (4 bytes).
    Removing system_stm32f4xx.o(.revsh_text), (4 bytes).
    Removing system_stm32f4xx.o(.rrx_text), (6 bytes).
    Removing system_stm32f4xx.o(i.SystemCoreClockUpdate), (192 bytes).
    Removing system_stm32f4xx.o(.constdata), (24 bytes).
    Removing system_stm32f4xx.o(.data), (4 bytes).

164 unused section(s) (total 22192 bytes) removed from the image.

==============================================================================

Image Symbol Table

    Local Symbols

    Symbol Name                              Value     Ov Type        Size  Object(Section)

    ../clib/angel/boardlib.s                 0x00000000   Number         0  boardinit3.o ABSOLUTE
    ../clib/angel/boardlib.s                 0x00000000   Number         0  boardinit2.o ABSOLUTE
    ../clib/angel/boardlib.s                 0x00000000   Number         0  boardinit1.o ABSOLUTE
    ../clib/angel/boardlib.s                 0x00000000   Number         0  boardshut.o ABSOLUTE
    ../clib/angel/handlers.s                 0x00000000   Number         0  __scatter_zi.o ABSOLUTE
    ../clib/angel/kernel.s                   0x00000000   Number         0  rtexit2.o ABSOLUTE
    ../clib/angel/kernel.s                   0x00000000   Number         0  __rtentry4.o ABSOLUTE
    ../clib/angel/kernel.s                   0x00000000   Number         0  __rtentry2.o ABSOLUTE
    ../clib/angel/kernel.s                   0x00000000   Number         0  __rtentry.o ABSOLUTE
    ../clib/angel/kernel.s                   0x00000000   Number         0  rtexit.o ABSOLUTE
    ../clib/angel/rt.s                       0x00000000   Number         0  rt_raise.o ABSOLUTE
    ../clib/angel/scatter.s                  0x00000000   Number         0  __scatter.o ABSOLUTE
    ../clib/angel/startup.s                  0x00000000   Number         0  __main.o ABSOLUTE
    ../clib/angel/sys.s                      0x00000000   Number         0  sys_stackheap_outer.o ABSOLUTE
    ../clib/angel/sys.s                      0x00000000   Number         0  use_no_semi.o ABSOLUTE
    ../clib/angel/sys.s                      0x00000000   Number         0  indicate_semi.o ABSOLUTE
    ../clib/angel/sys.s                      0x00000000   Number         0  libspace.o ABSOLUTE
    ../clib/angel/sysapp.c                   0x00000000   Number         0  sys_command.o ABSOLUTE
    ../clib/angel/sysapp.c                   0x00000000   Number         0  sys_wrch.o ABSOLUTE
    ../clib/angel/sysapp.c                   0x00000000   Number         0  sys_exit.o ABSOLUTE
    ../clib/armsys.c                         0x00000000   Number         0  _get_argv_nomalloc.o ABSOLUTE
    ../clib/armsys.c                         0x00000000   Number         0  argv_veneer.o ABSOLUTE
    ../clib/armsys.c                         0x00000000   Number         0  argv_veneer.o ABSOLUTE
    ../clib/armsys.c                         0x00000000   Number         0  no_argv.o ABSOLUTE
    ../clib/heapalloc.c                      0x00000000   Number         0  hrguard.o ABSOLUTE
    ../clib/heapaux.c                        0x00000000   Number         0  heapauxi.o ABSOLUTE
    ../clib/libinit.s                        0x00000000   Number         0  libshutdown.o ABSOLUTE
    ../clib/libinit.s                        0x00000000   Number         0  libshutdown2.o ABSOLUTE
    ../clib/libinit.s                        0x00000000   Number         0  libinit2.o ABSOLUTE
    ../clib/libinit.s                        0x00000000   Number         0  libinit.o ABSOLUTE
    ../clib/signal.c                         0x00000000   Number         0  defsig_fpe_inner.o ABSOLUTE
    ../clib/signal.c                         0x00000000   Number         0  defsig_abrt_inner.o ABSOLUTE
    ../clib/signal.c                         0x00000000   Number         0  defsig_general.o ABSOLUTE
    ../clib/signal.c                         0x00000000   Number         0  defsig_stak_inner.o ABSOLUTE
    ../clib/signal.c                         0x00000000   Number         0  __raise.o ABSOLUTE
    ../clib/signal.c                         0x00000000   Number         0  defsig_rtmem_inner.o ABSOLUTE
    ../clib/signal.c                         0x00000000   Number         0  defsig_rtmem_formal.o ABSOLUTE
    ../clib/signal.c                         0x00000000   Number         0  defsig_rtmem_outer.o ABSOLUTE
    ../clib/signal.c                         0x00000000   Number         0  defsig_other.o ABSOLUTE
    ../clib/signal.c                         0x00000000   Number         0  defsig_exit.o ABSOLUTE
    ../clib/signal.c                         0x00000000   Number         0  defsig_segv_inner.o ABSOLUTE
    ../clib/signal.c                         0x00000000   Number         0  defsig_cppl_inner.o ABSOLUTE
    ../clib/signal.c                         0x00000000   Number         0  defsig_pvfn_inner.o ABSOLUTE
    ../clib/signal.c                         0x00000000   Number         0  defsig_rtred_inner.o ABSOLUTE
    ../clib/signal.s                         0x00000000   Number         0  defsig.o ABSOLUTE
    ../clib/stdlib.c                         0x00000000   Number         0  exit.o ABSOLUTE
    ../fplib/fpinit.s                        0x00000000   Number         0  fpinit.o ABSOLUTE
    RTE/Device/STM32F401RETx/startup_stm32f401xe.s 0x00000000   Number         0  startup_stm32f401xe.o ABSOLUTE
    RTE/Device/STM32F401RETx/system_stm32f4xx.c 0x00000000   Number         0  system_stm32f4xx.o ABSOLUTE
    RTE\Device\STM32F401RETx\system_stm32f4xx.c 0x00000000   Number         0  system_stm32f4xx.o ABSOLUTE
    app\\main.c                              0x00000000   Number         0  main.o ABSOLUTE
    app\main.c                               0x00000000   Number         0  main.o ABSOLUTE
    dc.s                                     0x00000000   Number         0  dc.o ABSOLUTE
    hardware\\led.c                          0x00000000   Number         0  led.o ABSOLUTE
    hardware\led.c                           0x00000000   Number         0  led.o ABSOLUTE
    ucosii\Cfg\Template\app_hooks.c          0x00000000   Number         0  app_hooks.o ABSOLUTE
    ucosii\Ports\os_cpu_a.asm                0x00000000   Number         0  os_cpu_a.o ABSOLUTE
    ucosii\Ports\os_cpu_c.c                  0x00000000   Number         0  os_cpu_c.o ABSOLUTE
    ucosii\Source\os_core.c                  0x00000000   Number         0  os_core.o ABSOLUTE
    ucosii\Source\os_dbg_r.c                 0x00000000   Number         0  os_dbg_r.o ABSOLUTE
    ucosii\Source\os_flag.c                  0x00000000   Number         0  os_flag.o ABSOLUTE
    ucosii\Source\os_mbox.c                  0x00000000   Number         0  os_mbox.o ABSOLUTE
    ucosii\Source\os_mem.c                   0x00000000   Number         0  os_mem.o ABSOLUTE
    ucosii\Source\os_mutex.c                 0x00000000   Number         0  os_mutex.o ABSOLUTE
    ucosii\Source\os_q.c                     0x00000000   Number         0  os_q.o ABSOLUTE
    ucosii\Source\os_sem.c                   0x00000000   Number         0  os_sem.o ABSOLUTE
    ucosii\Source\os_task.c                  0x00000000   Number         0  os_task.o ABSOLUTE
    ucosii\Source\os_time.c                  0x00000000   Number         0  os_time.o ABSOLUTE
    ucosii\Source\os_tmr.c                   0x00000000   Number         0  os_tmr.o ABSOLUTE
    RESET                                    0x08000000   Section      404  startup_stm32f401xe.o(RESET)
    !!!main                                  0x08000194   Section        8  __main.o(!!!main)
    !!!scatter                               0x0800019c   Section       52  __scatter.o(!!!scatter)
    !!handler_zi                             0x080001d0   Section       28  __scatter_zi.o(!!handler_zi)
    .ARM.Collect$$libinit$$00000000          0x080001ec   Section        2  libinit.o(.ARM.Collect$$libinit$$00000000)
    .ARM.Collect$$libinit$$00000001          0x080001ee   Section        4  libinit2.o(.ARM.Collect$$libinit$$00000001)
    .ARM.Collect$$libinit$$00000004          0x080001f2   Section        0  libinit2.o(.ARM.Collect$$libinit$$00000004)
    .ARM.Collect$$libinit$$0000000A          0x080001f2   Section        0  libinit2.o(.ARM.Collect$$libinit$$0000000A)
    .ARM.Collect$$libinit$$0000000C          0x080001f2   Section        0  libinit2.o(.ARM.Collect$$libinit$$0000000C)
    .ARM.Collect$$libinit$$0000000E          0x080001f2   Section        0  libinit2.o(.ARM.Collect$$libinit$$0000000E)
    .ARM.Collect$$libinit$$00000011          0x080001f2   Section        0  libinit2.o(.ARM.Collect$$libinit$$00000011)
    .ARM.Collect$$libinit$$00000013          0x080001f2   Section        0  libinit2.o(.ARM.Collect$$libinit$$00000013)
    .ARM.Collect$$libinit$$00000015          0x080001f2   Section        0  libinit2.o(.ARM.Collect$$libinit$$00000015)
    .ARM.Collect$$libinit$$00000017          0x080001f2   Section        0  libinit2.o(.ARM.Collect$$libinit$$00000017)
    .ARM.Collect$$libinit$$00000019          0x080001f2   Section        0  libinit2.o(.ARM.Collect$$libinit$$00000019)
    .ARM.Collect$$libinit$$0000001B          0x080001f2   Section        0  libinit2.o(.ARM.Collect$$libinit$$0000001B)
    .ARM.Collect$$libinit$$0000001D          0x080001f2   Section        0  libinit2.o(.ARM.Collect$$libinit$$0000001D)
    .ARM.Collect$$libinit$$0000001F          0x080001f2   Section        0  libinit2.o(.ARM.Collect$$libinit$$0000001F)
    .ARM.Collect$$libinit$$00000021          0x080001f2   Section        0  libinit2.o(.ARM.Collect$$libinit$$00000021)
    .ARM.Collect$$libinit$$00000023          0x080001f2   Section        0  libinit2.o(.ARM.Collect$$libinit$$00000023)
    .ARM.Collect$$libinit$$00000025          0x080001f2   Section        0  libinit2.o(.ARM.Collect$$libinit$$00000025)
    .ARM.Collect$$libinit$$0000002C          0x080001f2   Section        0  libinit2.o(.ARM.Collect$$libinit$$0000002C)
    .ARM.Collect$$libinit$$0000002E          0x080001f2   Section        0  libinit2.o(.ARM.Collect$$libinit$$0000002E)
    .ARM.Collect$$libinit$$00000030          0x080001f2   Section        0  libinit2.o(.ARM.Collect$$libinit$$00000030)
    .ARM.Collect$$libinit$$00000032          0x080001f2   Section        0  libinit2.o(.ARM.Collect$$libinit$$00000032)
    .ARM.Collect$$libinit$$00000033          0x080001f2   Section        2  libinit2.o(.ARM.Collect$$libinit$$00000033)
    .ARM.Collect$$libshutdown$$00000000      0x080001f4   Section        2  libshutdown.o(.ARM.Collect$$libshutdown$$00000000)
    .ARM.Collect$$libshutdown$$00000002      0x080001f6   Section        0  libshutdown2.o(.ARM.Collect$$libshutdown$$00000002)
    .ARM.Collect$$libshutdown$$00000004      0x080001f6   Section        0  libshutdown2.o(.ARM.Collect$$libshutdown$$00000004)
    .ARM.Collect$$libshutdown$$00000007      0x080001f6   Section        0  libshutdown2.o(.ARM.Collect$$libshutdown$$00000007)
    .ARM.Collect$$libshutdown$$0000000A      0x080001f6   Section        0  libshutdown2.o(.ARM.Collect$$libshutdown$$0000000A)
    .ARM.Collect$$libshutdown$$0000000C      0x080001f6   Section        0  libshutdown2.o(.ARM.Collect$$libshutdown$$0000000C)
    .ARM.Collect$$libshutdown$$0000000F      0x080001f6   Section        0  libshutdown2.o(.ARM.Collect$$libshutdown$$0000000F)
    .ARM.Collect$$libshutdown$$00000010      0x080001f6   Section        2  libshutdown2.o(.ARM.Collect$$libshutdown$$00000010)
    .ARM.Collect$$rtentry$$00000000          0x080001f8   Section        0  __rtentry.o(.ARM.Collect$$rtentry$$00000000)
    .ARM.Collect$$rtentry$$00000002          0x080001f8   Section        0  __rtentry2.o(.ARM.Collect$$rtentry$$00000002)
    .ARM.Collect$$rtentry$$00000004          0x080001f8   Section        6  __rtentry4.o(.ARM.Collect$$rtentry$$00000004)
    .ARM.Collect$$rtentry$$00000009          0x080001fe   Section        0  __rtentry2.o(.ARM.Collect$$rtentry$$00000009)
    .ARM.Collect$$rtentry$$0000000A          0x080001fe   Section        4  __rtentry2.o(.ARM.Collect$$rtentry$$0000000A)
    .ARM.Collect$$rtentry$$0000000C          0x08000202   Section        0  __rtentry2.o(.ARM.Collect$$rtentry$$0000000C)
    .ARM.Collect$$rtentry$$0000000D          0x08000202   Section        8  __rtentry2.o(.ARM.Collect$$rtentry$$0000000D)
    .ARM.Collect$$rtexit$$00000000           0x0800020a   Section        2  rtexit.o(.ARM.Collect$$rtexit$$00000000)
    .ARM.Collect$$rtexit$$00000002           0x0800020c   Section        0  rtexit2.o(.ARM.Collect$$rtexit$$00000002)
    .ARM.Collect$$rtexit$$00000003           0x0800020c   Section        4  rtexit2.o(.ARM.Collect$$rtexit$$00000003)
    .ARM.Collect$$rtexit$$00000004           0x08000210   Section        6  rtexit2.o(.ARM.Collect$$rtexit$$00000004)
    .text                                    0x08000218   Section       64  startup_stm32f401xe.o(.text)
    $v0                                      0x08000218   Number         0  startup_stm32f401xe.o(.text)
    .text                                    0x08000258   Section        0  heapauxi.o(.text)
    .text                                    0x0800025e   Section       74  sys_stackheap_outer.o(.text)
    .text                                    0x080002a8   Section        0  exit.o(.text)
    .text                                    0x080002bc   Section        8  libspace.o(.text)
    .text                                    0x080002c4   Section        0  sys_exit.o(.text)
    .text                                    0x080002d0   Section        2  use_no_semi.o(.text)
    .text                                    0x080002d2   Section        0  indicate_semi.o(.text)
    i.FlashLED                               0x080002d4   Section        0  led.o(i.FlashLED)
    i.InitLED                                0x08000300   Section        0  led.o(i.InitLED)
    i.LED_Off                                0x08000354   Section        0  led.o(i.LED_Off)
    i.LED_On                                 0x08000368   Section        0  led.o(i.LED_On)
    i.SystemInit                             0x0800037c   Section        0  system_stm32f4xx.o(i.SystemInit)
    i.main                                   0x08000390   Section        0  main.o(i.main)
    x$fpl$fpinit                             0x0800039e   Section       10  fpinit.o(x$fpl$fpinit)
    $v0                                      0x0800039e   Number         0  fpinit.o(x$fpl$fpinit)
    .bss                                     0x20000000   Section       96  libspace.o(.bss)
    HEAP                                     0x20000060   Section      512  startup_stm32f401xe.o(HEAP)
    Heap_Mem                                 0x20000060   Data         512  startup_stm32f401xe.o(HEAP)
    STACK                                    0x20000260   Section     1024  startup_stm32f401xe.o(STACK)
    Stack_Mem                                0x20000260   Data        1024  startup_stm32f401xe.o(STACK)
    __initial_sp                             0x20000660   Data           0  startup_stm32f401xe.o(STACK)

    Global Symbols

    Symbol Name                              Value     Ov Type        Size  Object(Section)

    BuildAttributes$$THM_ISAv4$E$P$D$K$B$S$7EM$VFPi3$EXTD16$VFPS$VFMA$PE$A:L22UL41UL21$X:L11$S22US41US21$IEEE1$IW$USESV6$~STKCKD$USESV7$~SHL$OSPACE$ROPI$EBA8$UX$STANDARDLIB$REQ8$PRES8$EABIv2 0x00000000   Number         0  anon$$obj.o ABSOLUTE
    __ARM_use_no_argv                        0x00000000   Number         0  main.o ABSOLUTE
    __ARM_exceptions_init                     - Undefined Weak Reference
    __alloca_initialize                       - Undefined Weak Reference
    __arm_preinit_                            - Undefined Weak Reference
    __cpp_initialize__aeabi_                  - Undefined Weak Reference
    __cxa_finalize                            - Undefined Weak Reference
    __rt_locale                               - Undefined Weak Reference
    __sigvec_lookup                           - Undefined Weak Reference
    _atexit_init                              - Undefined Weak Reference
    _call_atexit_fns                          - Undefined Weak Reference
    _clock_init                               - Undefined Weak Reference
    _fp_trap_init                             - Undefined Weak Reference
    _fp_trap_shutdown                         - Undefined Weak Reference
    _get_lc_collate                           - Undefined Weak Reference
    _get_lc_ctype                             - Undefined Weak Reference
    _get_lc_monetary                          - Undefined Weak Reference
    _get_lc_numeric                           - Undefined Weak Reference
    _get_lc_time                              - Undefined Weak Reference
    _getenv_init                              - Undefined Weak Reference
    _handle_redirection                       - Undefined Weak Reference
    _init_alloc                               - Undefined Weak Reference
    _init_user_alloc                          - Undefined Weak Reference
    _initio                                   - Undefined Weak Reference
    _rand_init                                - Undefined Weak Reference
    _signal_finish                            - Undefined Weak Reference
    _signal_init                              - Undefined Weak Reference
    _terminate_alloc                          - Undefined Weak Reference
    _terminate_user_alloc                     - Undefined Weak Reference
    _terminateio                              - Undefined Weak Reference
    __Vectors_Size                           0x00000194   Number         0  startup_stm32f401xe.o ABSOLUTE
    __Vectors                                0x08000000   Data           4  startup_stm32f401xe.o(RESET)
    __Vectors_End                            0x08000194   Data           0  startup_stm32f401xe.o(RESET)
    __main                                   0x08000195   Thumb Code     8  __main.o(!!!main)
    __scatterload                            0x0800019d   Thumb Code     0  __scatter.o(!!!scatter)
    __scatterload_rt2                        0x0800019d   Thumb Code    44  __scatter.o(!!!scatter)
    __scatterload_rt2_thumb_only             0x0800019d   Thumb Code     0  __scatter.o(!!!scatter)
    __scatterload_null                       0x080001ab   Thumb Code     0  __scatter.o(!!!scatter)
    __scatterload_zeroinit                   0x080001d1   Thumb Code    28  __scatter_zi.o(!!handler_zi)
    __rt_lib_init                            0x080001ed   Thumb Code     0  libinit.o(.ARM.Collect$$libinit$$00000000)
    __rt_lib_init_fp_1                       0x080001ef   Thumb Code     0  libinit2.o(.ARM.Collect$$libinit$$00000001)
    __rt_lib_init_alloca_1                   0x080001f3   Thumb Code     0  libinit2.o(.ARM.Collect$$libinit$$0000002E)
    __rt_lib_init_argv_1                     0x080001f3   Thumb Code     0  libinit2.o(.ARM.Collect$$libinit$$0000002C)
    __rt_lib_init_atexit_1                   0x080001f3   Thumb Code     0  libinit2.o(.ARM.Collect$$libinit$$0000001B)
    __rt_lib_init_clock_1                    0x080001f3   Thumb Code     0  libinit2.o(.ARM.Collect$$libinit$$00000021)
    __rt_lib_init_cpp_1                      0x080001f3   Thumb Code     0  libinit2.o(.ARM.Collect$$libinit$$00000032)
    __rt_lib_init_exceptions_1               0x080001f3   Thumb Code     0  libinit2.o(.ARM.Collect$$libinit$$00000030)
    __rt_lib_init_fp_trap_1                  0x080001f3   Thumb Code     0  libinit2.o(.ARM.Collect$$libinit$$0000001F)
    __rt_lib_init_getenv_1                   0x080001f3   Thumb Code     0  libinit2.o(.ARM.Collect$$libinit$$00000023)
    __rt_lib_init_heap_1                     0x080001f3   Thumb Code     0  libinit2.o(.ARM.Collect$$libinit$$0000000A)
    __rt_lib_init_lc_collate_1               0x080001f3   Thumb Code     0  libinit2.o(.ARM.Collect$$libinit$$00000011)
    __rt_lib_init_lc_ctype_1                 0x080001f3   Thumb Code     0  libinit2.o(.ARM.Collect$$libinit$$00000013)
    __rt_lib_init_lc_monetary_1              0x080001f3   Thumb Code     0  libinit2.o(.ARM.Collect$$libinit$$00000015)
    __rt_lib_init_lc_numeric_1               0x080001f3   Thumb Code     0  libinit2.o(.ARM.Collect$$libinit$$00000017)
    __rt_lib_init_lc_time_1                  0x080001f3   Thumb Code     0  libinit2.o(.ARM.Collect$$libinit$$00000019)
    __rt_lib_init_preinit_1                  0x080001f3   Thumb Code     0  libinit2.o(.ARM.Collect$$libinit$$00000004)
    __rt_lib_init_rand_1                     0x080001f3   Thumb Code     0  libinit2.o(.ARM.Collect$$libinit$$0000000E)
    __rt_lib_init_return                     0x080001f3   Thumb Code     0  libinit2.o(.ARM.Collect$$libinit$$00000033)
    __rt_lib_init_signal_1                   0x080001f3   Thumb Code     0  libinit2.o(.ARM.Collect$$libinit$$0000001D)
    __rt_lib_init_stdio_1                    0x080001f3   Thumb Code     0  libinit2.o(.ARM.Collect$$libinit$$00000025)
    __rt_lib_init_user_alloc_1               0x080001f3   Thumb Code     0  libinit2.o(.ARM.Collect$$libinit$$0000000C)
    __rt_lib_shutdown                        0x080001f5   Thumb Code     0  libshutdown.o(.ARM.Collect$$libshutdown$$00000000)
    __rt_lib_shutdown_cpp_1                  0x080001f7   Thumb Code     0  libshutdown2.o(.ARM.Collect$$libshutdown$$00000002)
    __rt_lib_shutdown_fp_trap_1              0x080001f7   Thumb Code     0  libshutdown2.o(.ARM.Collect$$libshutdown$$00000007)
    __rt_lib_shutdown_heap_1                 0x080001f7   Thumb Code     0  libshutdown2.o(.ARM.Collect$$libshutdown$$0000000F)
    __rt_lib_shutdown_return                 0x080001f7   Thumb Code     0  libshutdown2.o(.ARM.Collect$$libshutdown$$00000010)
    __rt_lib_shutdown_signal_1               0x080001f7   Thumb Code     0  libshutdown2.o(.ARM.Collect$$libshutdown$$0000000A)
    __rt_lib_shutdown_stdio_1                0x080001f7   Thumb Code     0  libshutdown2.o(.ARM.Collect$$libshutdown$$00000004)
    __rt_lib_shutdown_user_alloc_1           0x080001f7   Thumb Code     0  libshutdown2.o(.ARM.Collect$$libshutdown$$0000000C)
    __rt_entry                               0x080001f9   Thumb Code     0  __rtentry.o(.ARM.Collect$$rtentry$$00000000)
    __rt_entry_presh_1                       0x080001f9   Thumb Code     0  __rtentry2.o(.ARM.Collect$$rtentry$$00000002)
    __rt_entry_sh                            0x080001f9   Thumb Code     0  __rtentry4.o(.ARM.Collect$$rtentry$$00000004)
    __rt_entry_li                            0x080001ff   Thumb Code     0  __rtentry2.o(.ARM.Collect$$rtentry$$0000000A)
    __rt_entry_postsh_1                      0x080001ff   Thumb Code     0  __rtentry2.o(.ARM.Collect$$rtentry$$00000009)
    __rt_entry_main                          0x08000203   Thumb Code     0  __rtentry2.o(.ARM.Collect$$rtentry$$0000000D)
    __rt_entry_postli_1                      0x08000203   Thumb Code     0  __rtentry2.o(.ARM.Collect$$rtentry$$0000000C)
    __rt_exit                                0x0800020b   Thumb Code     0  rtexit.o(.ARM.Collect$$rtexit$$00000000)
    __rt_exit_ls                             0x0800020d   Thumb Code     0  rtexit2.o(.ARM.Collect$$rtexit$$00000003)
    __rt_exit_prels_1                        0x0800020d   Thumb Code     0  rtexit2.o(.ARM.Collect$$rtexit$$00000002)
    __rt_exit_exit                           0x08000211   Thumb Code     0  rtexit2.o(.ARM.Collect$$rtexit$$00000004)
    Reset_Handler                            0x08000219   Thumb Code     8  startup_stm32f401xe.o(.text)
    NMI_Handler                              0x08000221   Thumb Code     2  startup_stm32f401xe.o(.text)
    HardFault_Handler                        0x08000223   Thumb Code     2  startup_stm32f401xe.o(.text)
    MemManage_Handler                        0x08000225   Thumb Code     2  startup_stm32f401xe.o(.text)
    BusFault_Handler                         0x08000227   Thumb Code     2  startup_stm32f401xe.o(.text)
    UsageFault_Handler                       0x08000229   Thumb Code     2  startup_stm32f401xe.o(.text)
    SVC_Handler                              0x0800022b   Thumb Code     2  startup_stm32f401xe.o(.text)
    DebugMon_Handler                         0x0800022d   Thumb Code     2  startup_stm32f401xe.o(.text)
    PendSV_Handler                           0x0800022f   Thumb Code     2  startup_stm32f401xe.o(.text)
    SysTick_Handler                          0x08000231   Thumb Code     2  startup_stm32f401xe.o(.text)
    ADC_IRQHandler                           0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    DMA1_Stream0_IRQHandler                  0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    DMA1_Stream1_IRQHandler                  0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    DMA1_Stream2_IRQHandler                  0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    DMA1_Stream3_IRQHandler                  0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    DMA1_Stream4_IRQHandler                  0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    DMA1_Stream5_IRQHandler                  0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    DMA1_Stream6_IRQHandler                  0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    DMA1_Stream7_IRQHandler                  0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    DMA2_Stream0_IRQHandler                  0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    DMA2_Stream1_IRQHandler                  0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    DMA2_Stream2_IRQHandler                  0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    DMA2_Stream3_IRQHandler                  0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    DMA2_Stream4_IRQHandler                  0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    DMA2_Stream5_IRQHandler                  0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    DMA2_Stream6_IRQHandler                  0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    DMA2_Stream7_IRQHandler                  0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    EXTI0_IRQHandler                         0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    EXTI15_10_IRQHandler                     0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    EXTI1_IRQHandler                         0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    EXTI2_IRQHandler                         0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    EXTI3_IRQHandler                         0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    EXTI4_IRQHandler                         0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    EXTI9_5_IRQHandler                       0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    FLASH_IRQHandler                         0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    FPU_IRQHandler                           0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    I2C1_ER_IRQHandler                       0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    I2C1_EV_IRQHandler                       0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    I2C2_ER_IRQHandler                       0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    I2C2_EV_IRQHandler                       0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    I2C3_ER_IRQHandler                       0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    I2C3_EV_IRQHandler                       0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    OTG_FS_IRQHandler                        0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    OTG_FS_WKUP_IRQHandler                   0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    PVD_IRQHandler                           0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    RCC_IRQHandler                           0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    RTC_Alarm_IRQHandler                     0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    RTC_WKUP_IRQHandler                      0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    SDIO_IRQHandler                          0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    SPI1_IRQHandler                          0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    SPI2_IRQHandler                          0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    SPI3_IRQHandler                          0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    SPI4_IRQHandler                          0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    TAMP_STAMP_IRQHandler                    0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    TIM1_BRK_TIM9_IRQHandler                 0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    TIM1_CC_IRQHandler                       0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    TIM1_TRG_COM_TIM11_IRQHandler            0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    TIM1_UP_TIM10_IRQHandler                 0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    TIM2_IRQHandler                          0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    TIM3_IRQHandler                          0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    TIM4_IRQHandler                          0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    TIM5_IRQHandler                          0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    USART1_IRQHandler                        0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    USART2_IRQHandler                        0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    USART6_IRQHandler                        0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    WWDG_IRQHandler                          0x08000233   Thumb Code     0  startup_stm32f401xe.o(.text)
    __user_initial_stackheap                 0x08000235   Thumb Code     0  startup_stm32f401xe.o(.text)
    __use_two_region_memory                  0x08000259   Thumb Code     2  heapauxi.o(.text)
    __rt_heap_escrow$2region                 0x0800025b   Thumb Code     2  heapauxi.o(.text)
    __rt_heap_expand$2region                 0x0800025d   Thumb Code     2  heapauxi.o(.text)
    __user_setup_stackheap                   0x0800025f   Thumb Code    74  sys_stackheap_outer.o(.text)
    exit                                     0x080002a9   Thumb Code    18  exit.o(.text)
    __user_libspace                          0x080002bd   Thumb Code     8  libspace.o(.text)
    __user_perproc_libspace                  0x080002bd   Thumb Code     0  libspace.o(.text)
    __user_perthread_libspace                0x080002bd   Thumb Code     0  libspace.o(.text)
    _sys_exit                                0x080002c5   Thumb Code     8  sys_exit.o(.text)
    __I$use$semihosting                      0x080002d1   Thumb Code     0  use_no_semi.o(.text)
    __use_no_semihosting_swi                 0x080002d1   Thumb Code     2  use_no_semi.o(.text)
    __semihosting_library_function           0x080002d3   Thumb Code     0  indicate_semi.o(.text)
    FlashLED                                 0x080002d5   Thumb Code    38  led.o(i.FlashLED)
    InitLED                                  0x08000301   Thumb Code    74  led.o(i.InitLED)
    LED_Off                                  0x08000355   Thumb Code    14  led.o(i.LED_Off)
    LED_On                                   0x08000369   Thumb Code    14  led.o(i.LED_On)
    SystemInit                               0x0800037d   Thumb Code    14  system_stm32f4xx.o(i.SystemInit)
    main                                     0x08000391   Thumb Code    14  main.o(i.main)
    _fp_init                                 0x0800039f   Thumb Code    10  fpinit.o(x$fpl$fpinit)
    __fplib_config_fpu_vfp                   0x080003a7   Thumb Code     0  fpinit.o(x$fpl$fpinit)
    __fplib_config_pureend_doubles           0x080003a7   Thumb Code     0  fpinit.o(x$fpl$fpinit)
    Region$$Table$$Base                      0x080003a8   Number         0  anon$$obj.o(Region$$Table)
    Region$$Table$$Limit                     0x080003b8   Number         0  anon$$obj.o(Region$$Table)
    __libspace_start                         0x20000000   Data          96  libspace.o(.bss)
    __temporary_stack_top$libspace           0x20000060   Data           0  libspace.o(.bss)



==============================================================================

Memory Map of the image

  Image Entry point : 0x08000195

  Load Region LR_IROM1 (Base: 0x08000000, Size: 0x000003b8, Max: 0x00080000, ABSOLUTE)

    Execution Region ER_IROM1 (Exec base: 0x08000000, Load base: 0x08000000, Size: 0x000003b8, Max: 0x00080000, ABSOLUTE)

    Exec Addr    Load Addr    Size         Type   Attr      Idx    E Section Name        Object

    0x08000000   0x08000000   0x00000194   Data   RO         1094    RESET               startup_stm32f401xe.o
    0x08000194   0x08000194   0x00000008   Code   RO         1140  * !!!main             c_w.l(__main.o)
    0x0800019c   0x0800019c   0x00000034   Code   RO         1297    !!!scatter          c_w.l(__scatter.o)
    0x080001d0   0x080001d0   0x0000001c   Code   RO         1299    !!handler_zi        c_w.l(__scatter_zi.o)
    0x080001ec   0x080001ec   0x00000002   Code   RO         1167    .ARM.Collect$$libinit$$00000000  c_w.l(libinit.o)
    0x080001ee   0x080001ee   0x00000004   Code   RO         1173    .ARM.Collect$$libinit$$00000001  c_w.l(libinit2.o)
    0x080001f2   0x080001f2   0x00000000   Code   RO         1176    .ARM.Collect$$libinit$$00000004  c_w.l(libinit2.o)
    0x080001f2   0x080001f2   0x00000000   Code   RO         1179    .ARM.Collect$$libinit$$0000000A  c_w.l(libinit2.o)
    0x080001f2   0x080001f2   0x00000000   Code   RO         1181    .ARM.Collect$$libinit$$0000000C  c_w.l(libinit2.o)
    0x080001f2   0x080001f2   0x00000000   Code   RO         1183    .ARM.Collect$$libinit$$0000000E  c_w.l(libinit2.o)
    0x080001f2   0x080001f2   0x00000000   Code   RO         1186    .ARM.Collect$$libinit$$00000011  c_w.l(libinit2.o)
    0x080001f2   0x080001f2   0x00000000   Code   RO         1188    .ARM.Collect$$libinit$$00000013  c_w.l(libinit2.o)
    0x080001f2   0x080001f2   0x00000000   Code   RO         1190    .ARM.Collect$$libinit$$00000015  c_w.l(libinit2.o)
    0x080001f2   0x080001f2   0x00000000   Code   RO         1192    .ARM.Collect$$libinit$$00000017  c_w.l(libinit2.o)
    0x080001f2   0x080001f2   0x00000000   Code   RO         1194    .ARM.Collect$$libinit$$00000019  c_w.l(libinit2.o)
    0x080001f2   0x080001f2   0x00000000   Code   RO         1196    .ARM.Collect$$libinit$$0000001B  c_w.l(libinit2.o)
    0x080001f2   0x080001f2   0x00000000   Code   RO         1198    .ARM.Collect$$libinit$$0000001D  c_w.l(libinit2.o)
    0x080001f2   0x080001f2   0x00000000   Code   RO         1200    .ARM.Collect$$libinit$$0000001F  c_w.l(libinit2.o)
    0x080001f2   0x080001f2   0x00000000   Code   RO         1202    .ARM.Collect$$libinit$$00000021  c_w.l(libinit2.o)
    0x080001f2   0x080001f2   0x00000000   Code   RO         1204    .ARM.Collect$$libinit$$00000023  c_w.l(libinit2.o)
    0x080001f2   0x080001f2   0x00000000   Code   RO         1206    .ARM.Collect$$libinit$$00000025  c_w.l(libinit2.o)
    0x080001f2   0x080001f2   0x00000000   Code   RO         1210    .ARM.Collect$$libinit$$0000002C  c_w.l(libinit2.o)
    0x080001f2   0x080001f2   0x00000000   Code   RO         1212    .ARM.Collect$$libinit$$0000002E  c_w.l(libinit2.o)
    0x080001f2   0x080001f2   0x00000000   Code   RO         1214    .ARM.Collect$$libinit$$00000030  c_w.l(libinit2.o)
    0x080001f2   0x080001f2   0x00000000   Code   RO         1216    .ARM.Collect$$libinit$$00000032  c_w.l(libinit2.o)
    0x080001f2   0x080001f2   0x00000002   Code   RO         1217    .ARM.Collect$$libinit$$00000033  c_w.l(libinit2.o)
    0x080001f4   0x080001f4   0x00000002   Code   RO         1237    .ARM.Collect$$libshutdown$$00000000  c_w.l(libshutdown.o)
    0x080001f6   0x080001f6   0x00000000   Code   RO         1250    .ARM.Collect$$libshutdown$$00000002  c_w.l(libshutdown2.o)
    0x080001f6   0x080001f6   0x00000000   Code   RO         1252    .ARM.Collect$$libshutdown$$00000004  c_w.l(libshutdown2.o)
    0x080001f6   0x080001f6   0x00000000   Code   RO         1255    .ARM.Collect$$libshutdown$$00000007  c_w.l(libshutdown2.o)
    0x080001f6   0x080001f6   0x00000000   Code   RO         1258    .ARM.Collect$$libshutdown$$0000000A  c_w.l(libshutdown2.o)
    0x080001f6   0x080001f6   0x00000000   Code   RO         1260    .ARM.Collect$$libshutdown$$0000000C  c_w.l(libshutdown2.o)
    0x080001f6   0x080001f6   0x00000000   Code   RO         1263    .ARM.Collect$$libshutdown$$0000000F  c_w.l(libshutdown2.o)
    0x080001f6   0x080001f6   0x00000002   Code   RO         1264    .ARM.Collect$$libshutdown$$00000010  c_w.l(libshutdown2.o)
    0x080001f8   0x080001f8   0x00000000   Code   RO         1142    .ARM.Collect$$rtentry$$00000000  c_w.l(__rtentry.o)
    0x080001f8   0x080001f8   0x00000000   Code   RO         1144    .ARM.Collect$$rtentry$$00000002  c_w.l(__rtentry2.o)
    0x080001f8   0x080001f8   0x00000006   Code   RO         1156    .ARM.Collect$$rtentry$$00000004  c_w.l(__rtentry4.o)
    0x080001fe   0x080001fe   0x00000000   Code   RO         1146    .ARM.Collect$$rtentry$$00000009  c_w.l(__rtentry2.o)
    0x080001fe   0x080001fe   0x00000004   Code   RO         1147    .ARM.Collect$$rtentry$$0000000A  c_w.l(__rtentry2.o)
    0x08000202   0x08000202   0x00000000   Code   RO         1149    .ARM.Collect$$rtentry$$0000000C  c_w.l(__rtentry2.o)
    0x08000202   0x08000202   0x00000008   Code   RO         1150    .ARM.Collect$$rtentry$$0000000D  c_w.l(__rtentry2.o)
    0x0800020a   0x0800020a   0x00000002   Code   RO         1171    .ARM.Collect$$rtexit$$00000000  c_w.l(rtexit.o)
    0x0800020c   0x0800020c   0x00000000   Code   RO         1219    .ARM.Collect$$rtexit$$00000002  c_w.l(rtexit2.o)
    0x0800020c   0x0800020c   0x00000004   Code   RO         1220    .ARM.Collect$$rtexit$$00000003  c_w.l(rtexit2.o)
    0x08000210   0x08000210   0x00000006   Code   RO         1221    .ARM.Collect$$rtexit$$00000004  c_w.l(rtexit2.o)
    0x08000216   0x08000216   0x00000002   PAD
    0x08000218   0x08000218   0x00000040   Code   RO         1095    .text               startup_stm32f401xe.o
    0x08000258   0x08000258   0x00000006   Code   RO         1138    .text               c_w.l(heapauxi.o)
    0x0800025e   0x0800025e   0x0000004a   Code   RO         1158    .text               c_w.l(sys_stackheap_outer.o)
    0x080002a8   0x080002a8   0x00000012   Code   RO         1160    .text               c_w.l(exit.o)
    0x080002ba   0x080002ba   0x00000002   PAD
    0x080002bc   0x080002bc   0x00000008   Code   RO         1168    .text               c_w.l(libspace.o)
    0x080002c4   0x080002c4   0x0000000c   Code   RO         1229    .text               c_w.l(sys_exit.o)
    0x080002d0   0x080002d0   0x00000002   Code   RO         1240    .text               c_w.l(use_no_semi.o)
    0x080002d2   0x080002d2   0x00000000   Code   RO         1242    .text               c_w.l(indicate_semi.o)
    0x080002d2   0x080002d2   0x00000002   PAD
    0x080002d4   0x080002d4   0x0000002c   Code   RO            4    i.FlashLED          led.o
    0x08000300   0x08000300   0x00000054   Code   RO            5    i.InitLED           led.o
    0x08000354   0x08000354   0x00000014   Code   RO            6    i.LED_Off           led.o
    0x08000368   0x08000368   0x00000014   Code   RO            7    i.LED_On            led.o
    0x0800037c   0x0800037c   0x00000014   Code   RO         1103    i.SystemInit        system_stm32f4xx.o
    0x08000390   0x08000390   0x0000000e   Code   RO           81    i.main              main.o
    0x0800039e   0x0800039e   0x0000000a   Code   RO         1227    x$fpl$fpinit        fz_wm.l(fpinit.o)
    0x080003a8   0x080003a8   0x00000010   Data   RO         1295    Region$$Table       anon$$obj.o


    Execution Region RW_IRAM1 (Exec base: 0x20000000, Load base: 0x080003b8, Size: 0x00000660, Max: 0x00018000, ABSOLUTE)

    Exec Addr    Load Addr    Size         Type   Attr      Idx    E Section Name        Object

    0x20000000        -       0x00000060   Zero   RW         1169    .bss                c_w.l(libspace.o)
    0x20000060        -       0x00000200   Zero   RW         1093    HEAP                startup_stm32f401xe.o
    0x20000260        -       0x00000400   Zero   RW         1092    STACK               startup_stm32f401xe.o


==============================================================================

Image component sizes


      Code (inc. data)   RO Data    RW Data    ZI Data      Debug   Object Name

       168         28          0          0          0       3288   led.o
        14          0          0          0          0        463   main.o
        64         26        404          0       1536        860   startup_stm32f401xe.o
        20          6          0          0          0        493   system_stm32f4xx.o

    ----------------------------------------------------------------------
       266         60        420          0       1536       5104   Object Totals
         0          0         16          0          0          0   (incl. Generated)
         0          0          0          0          0          0   (incl. Padding)

    ----------------------------------------------------------------------

      Code (inc. data)   RO Data    RW Data    ZI Data      Debug   Library Member Name

         8          0          0          0          0         68   __main.o
         0          0          0          0          0          0   __rtentry.o
        12          0          0          0          0          0   __rtentry2.o
         6          0          0          0          0          0   __rtentry4.o
        52          8          0          0          0          0   __scatter.o
        28          0          0          0          0          0   __scatter_zi.o
        18          0          0          0          0         80   exit.o
         6          0          0          0          0        152   heapauxi.o
         0          0          0          0          0          0   indicate_semi.o
         2          0          0          0          0          0   libinit.o
         6          0          0          0          0          0   libinit2.o
         2          0          0          0          0          0   libshutdown.o
         2          0          0          0          0          0   libshutdown2.o
         8          4          0          0         96         68   libspace.o
         2          0          0          0          0          0   rtexit.o
        10          0          0          0          0          0   rtexit2.o
        12          4          0          0          0         68   sys_exit.o
        74          0          0          0          0         80   sys_stackheap_outer.o
         2          0          0          0          0         68   use_no_semi.o
        10          0          0          0          0        116   fpinit.o

    ----------------------------------------------------------------------
       266         16          0          0         96        700   Library Totals
         6          0          0          0          0          0   (incl. Padding)

    ----------------------------------------------------------------------

      Code (inc. data)   RO Data    RW Data    ZI Data      Debug   Library Name

       250         16          0          0         96        584   c_w.l
        10          0          0          0          0        116   fz_wm.l

    ----------------------------------------------------------------------
       266         16          0          0         96        700   Library Totals

    ----------------------------------------------------------------------

==============================================================================


      Code (inc. data)   RO Data    RW Data    ZI Data      Debug   

       532         76        420          0       1632       5280   Grand Totals
       532         76        420          0       1632       5280   ELF Image Totals
       532         76        420          0          0          0   ROM Totals

==============================================================================

    Total RO  Size (Code + RO Data)                  952 (   0.93kB)
    Total RW  Size (RW Data + ZI Data)              1632 (   1.59kB)
    Total ROM Size (Code + RO Data + RW Data)        952 (   0.93kB)

==============================================================================```
```
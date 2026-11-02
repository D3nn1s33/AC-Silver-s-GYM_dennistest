# Graph Report - AC-Silver-s-GYM_dennistest  (2026-11-01)

## Corpus Check
- 210 files · ~241,695 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 4723 nodes · 11382 edges · 176 communities (143 shown, 33 thin omitted)
- Extraction: 90% EXTRACTED · 10% INFERRED · 0% AMBIGUOUS · INFERRED: 1102 edges (avg confidence: 0.9)
- Token cost: 400,501 input · 0 output

## Community Hubs (Navigation)
- Fachada GymService
- Consultas especiales tipadas
- Pruebas inventario y tienda
- Mappers de Supabase
- Agregado GymDomainService
- Vista Tienda y carrito
- Dependencias y pruebas frontend
- Contratos PostgreSQL y validador
- Rutas y arranque FastAPI
- Pruebas de prioridad y alcance
- Vista Inventario
- Documentacion Spec Kit y modulos
- Landing y paginas publicas
- Horarios por servicio
- Rutas de matricula y errores HTTP
- Movimientos de inventario
- Monitoreo de rutinas del entrenador
- Contratos de repositorio
- Servicio de clientes
- Fachadas Local y Supabase
- Checkout de tienda y pagos
- Matricula del cliente
- Operaciones de cuentas
- Router y paneles por rol
- Funcion Edge de correos
- Directorio de clientes
- Servicio de asistencia
- Contexto de reglas de dominio
- Modulos de aplicacion frontend
- Reglas de horarios
- Promociones y tema visual
- Stores de Pinia
- Operaciones de tienda
- Refresco remoto de Supabase
- Reglas de pagos y fechas
- Panel de inicio
- Repositorio Supabase
- Configuracion y Google
- Docker Compose
- Workflow de validacion de PR
- Reglas de membresias
- Operaciones de horarios
- Operaciones de membresias
- Notificaciones por correo
- Planes y validacion de formularios
- Componentes del repositorio
- Navegacion de modulos
- Asistencia del cliente
- Grilla de horarios Excel
- Rutinas del entrenador
- Reglas de cuentas
- InventoryMovementsView.vue
- re
- StoreMovementsPanel.vue
- Spec 000 Base implementada
- SupabaseRestClient
- Regla: Seguridad y límites de acceso
- attendance_routes.py
- InventoryRules
- security.py
- RegisterView.vue
- StorePaymentView.vue
- ExtensibleSelect.vue
- UsersView.vue
- domain/errors.py
- StoreRules
- SupabaseGymRepository
- StripeService
- AttendanceHistory.vue
- ref_node_assert
- Guia practica chatbot con Spec Kit
- bootstrap.py
- auth_service.py
- gym.py
- common.sh
- Preámbulo común de etapas Spec Kit
- clientIdentity.js
- utils/attendance.js
- MembershipPaymentsView.vue
- 11-schedule-enrollment.test.js
- apiClient.js
- OrdersView.vue
- test_stripe_confirmation.py
- operations/attendance.py
- inputRules.js
- lucide-vue-next
- Constitucion de AC Silver's GYM
- store_images_service.py
- test_maintainability_fixes.py
- test_admin_client_payment.py
- bootstrap.js
- http_transport.py
- test_module_error_control.py
- test_membership_expiration.py
- 23-layer-boundaries.test.js
- operations/inventory.py
- AttendanceRules
- LoginView.vue
- IntegrationTests
- steps
- test_layer_boundaries.py
- create_pedido_checkout()
- test_review_regressions.py
- MemoryGymRepository
- attendanceService.js
- AttendanceCorrectionDialog.vue
- create-new-feature.sh
- SchemaNotReady
- backend requirements.txt
- ProductEditorDialog.vue
- services
- test_basic_form_validation.py
- membership_lifecycle.py
- operations/configuration.py
- with
- email_templates.py
- mappers/store.py
- StoreMovementsPanelView.vue
- jobs
- trainer_routes.py
- _schedule_service()
- SessionProvider
- publicStorage.js
- mappers/inventory.py
- vercel.json
- clientDashboard.js
- ConfirmDialog.vue
- ResourceModal.vue
- buildSignature()
- docker-ci
- exportCsv()
- norm()
- buildPayload()
- deploy-vercel
- Tasks template (override)
- atomic_fake.py
- rickroll.gif (Rick Astley 'Never Gonna G
- SortableTh.vue
- deploy-render
- interface
- validate.py (hook de validación)
- PromocionInput
- _RouteService
- frontend index.html
- backend-ci
- schedule-emails-ci
- test_date_boundary_uses_peru_midnight()
- favicon.svg (Vite lightning-bolt logo)
- pull_request
- Release 1.1.0 MVP (2026-09-15)
- SearchInput.vue
- Checklist template
- test_promocion_cupos.py
- clearFilters()

## God Nodes (most connected - your core abstractions)
1. `GymService` - 218 edges
2. `DomainComponents` - 182 edges
3. `GymDomainService` - 179 edges
4. `Record` - 149 edges
5. `Resource` - 95 edges
6. `vue` - 87 edges
7. `SupabaseGymRepository` - 55 edges
8. `http_error()` - 52 edges
9. `ClientsService` - 51 edges
10. `StoreOperations` - 46 edges

## Surprising Connections (you probably didn't know these)
- `commit_gym_transaction atomico` --semantically_similar_to--> `commit_gym_transaction RPC`  [INFERRED] [semantically similar]
  README.md → .specify/memory/constitution.md
- `No iniciar Spec Kit hasta peticion expresa` --semantically_similar_to--> `Activacion explicita de Spec Kit por el usuario`  [INFERRED] [semantically similar]
  AGENTS.md → .specify/guias/spec-driven.md
- `Arquitectura de cuatro capas backend/frontend` --conceptually_related_to--> `II. Respetar capas y reutilizar mecanismos`  [INFERRED]
  README.md → .specify/memory/constitution.md
- `test_promocion_limite_cupos_exhaustion()` --uses--> `GymDomainService`  [INFERRED]
  backend/tests/test_promocion_cupos.py → backend/domain/services/gym_domain_service.py
- `test()` --calls--> `get_gym_service()`  [INFERRED]
  backend/tests/manual/fetch_memberships.py → backend/presentation/dependencies.py

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Hero banner composition: athlete subject + dark style + gym hero section** — frontend_src_presentation_assets_hero_banner_athlete_barbell_curl, frontend_src_presentation_assets_hero_banner_dark_brick_wall_style, frontend_src_presentation_assets_hero_banner_gym_branding_hero [INFERRED 0.85]
- **Pipeline de etapas Spec Kit (specify, plan, tasks, analyze, implement, converge)** — _specify__codex_skills_speckit_specify_skill, _specify__codex_skills_speckit_plan_skill, _specify__codex_skills_speckit_tasks_skill, _specify__codex_skills_speckit_analyze_skill, _specify__codex_skills_speckit_implement_skill, _specify__codex_skills_speckit_converge_skill, _specify__codex_skills_gym_spec_driven_skill [EXTRACTED 1.00]
- **Puntos que ejecutan el hook validate.py** — _specify__codex_hooks_readme_validate_py, specify_scripts_bash_setup_plan, specify_scripts_bash_check_prerequisites, _specify__codex_hooks_readme_etapas_hook [EXTRACTED 1.00]
- **Control de acceso y atomicidad en servidor** — _specify__codex_rules_seguridad_matriz_acceso, _specify__codex_rules_seguridad_authservice, _specify__codex_rules_seguridad_service_role_rpc, _specify__codex_rules_datos_commit_gym_transaction, _specify__codex_rules_seguridad_stripe_webhook [INFERRED 0.85]
- **Contratos de los once módulos funcionales** — _specify_base_modulos_01_identidad_acceso, _specify_base_modulos_02_clientes, _specify_base_modulos_03_membresias_pagos, _specify_base_modulos_04_planes_promociones, _specify_base_modulos_05_horarios_matriculas, _specify_base_modulos_06_asistencias, _specify_base_modulos_07_rutinas_progreso, _specify_base_modulos_08_inventario, _specify_base_modulos_09_tienda_pedidos, _specify_base_modulos_10_paneles_configuracion, _specify_base_modulos_11_notificaciones [EXTRACTED 1.00]
- **Persistencia atómica del backend** — _specify_docs_arquitectura_gymservice, _specify_docs_arquitectura_gymrepository, _specify_docs_arquitectura_resource, _specify_docs_arquitectura_migraciones_014_015_016 [EXTRACTED 1.00]
- **Aislamiento de sesión en frontend** — frontend_src_application_services_gymmodules, frontend_src_bootstrap [INFERRED 0.85]
- **Plantillas override de Spec Kit del gimnasio** — _specify_templates_overrides_context_template, _specify_templates_overrides_spec_template, _specify_templates_overrides_plan_template, _specify_templates_overrides_tasks_template [INFERRED 0.95]
- **Puertas de etapa via hook validate.py** — _specify_guias_estructura_codex_validate_py, specify_scripts_bash_setup_plan, _specify_guias_spec_driven_check_prerequisites_sh, _specify_templates_overrides_tasks_template_cierre_hook_close, agents_comprobaciones_raiz [INFERRED 0.85]
- **Principios I-VII de la constitucion** — _specify_memory_constitution_i_especificar_base, _specify_memory_constitution_ii_capas_reutilizar, _specify_memory_constitution_iii_operaciones_completas, _specify_memory_constitution_iv_autorizar_servidor, _specify_memory_constitution_v_reglas_economicas_temporales, _specify_memory_constitution_vi_evidencia_proporcional, _specify_memory_constitution_vii_contratos_vivos [EXTRACTED 1.00]

## Communities (176 total, 33 thin omitted)

### Community 0 - "Fachada GymService"
Cohesion: 0.05
Nodes (13): GymService, StoreOperations, list_inventario(), list_movimientos(), list_membresias(), list_planes_membresia(), membresias_por_cliente(), list_promociones() (+5 more)

### Community 1 - "Consultas especiales tipadas"
Cohesion: 0.05
Nodes (14): Record, AccountForSessionQuery, AttendanceEnrollmentsQuery, AttendanceHistoryQuery, EnrollScheduleCommand, ExpireMembershipsCommand, LatestMembershipQuery, LegacySnapshotQuery (+6 more)

### Community 2 - "Pruebas inventario y tienda"
Cohesion: 0.08
Nodes (57): test_admin_schema_is_required_instead_of_silently_dropping_origin(), test_client_lookup_does_not_return_an_unrelated_client(), test_client_lookup_preserves_identity_priority(), test_enrollment_errors_keep_their_business_meaning(), test_unknown_storage_error_is_not_hidden_as_a_validation_error(), _actualizaciones(), _estado(), FakeSupabase (+49 more)

### Community 3 - "Mappers de Supabase"
Cohesion: 0.06
Nodes (45): AttendanceCriteria, AttendancePage, AttendanceSummaryData, PageRequest, user_role_prefix(), parse_client_id(), normalize_membership_status(), AttendanceHistoryRepository (+37 more)

### Community 5 - "Vista Tienda y carrito"
Cohesion: 0.03
Nodes (60): cleanInteger(), activeTab, addDetailToCart(), agregarAlCarrito(), authStore, availableFor(), blockQuantityChars, busqueda (+52 more)

### Community 6 - "Dependencias y pruebas frontend"
Cohesion: 0.04
Nodes (53): dependencies, autoprefixer@^10.5.0, chart.js@^4.5.1, @fortawesome/fontawesome-free@^7.3.1, @fullcalendar/core@^6.1.20, @fullcalendar/interaction@^6.1.20, @fullcalendar/timegrid@^6.1.20, @fullcalendar/vue3@^6.1.20 (+45 more)

### Community 7 - "Contratos PostgreSQL y validador"
Cohesion: 0.06
Nodes (39): test(), test(), test(), clear(), database(), Postgres, service(), test_client_deletion_cascades_atomically_with_restrictive_foreign_keys() (+31 more)

### Community 8 - "Rutas y arranque FastAPI"
Cohesion: 0.06
Nodes (26): health(), lifespan(), root(), get_clients_service(), get_current_user(), get_gym_service(), get_identity_service(), get_optional_actor_id() (+18 more)

### Community 9 - "Pruebas de prioridad y alcance"
Cohesion: 0.04
Nodes (31): UsersService, AccountsDependencies, Passwords, protected_api(), headers(), test_business_fields_survive_round_trip(), test_domain_date_and_time_use_lima(), test_image_upload_requires_staff_but_listing_remains_public() (+23 more)

### Community 10 - "Vista Inventario"
Cohesion: 0.04
Nodes (57): INVENTORY_CATEGORIES, INVENTORY_LOCATIONS, INVENTORY_UNITS, inventoryOptions(), activeTab, blockNameChars, categoryDotPalette, categoryOptions (+49 more)

### Community 11 - "Documentacion Spec Kit y modulos"
Cohesion: 0.07
Nodes (58): Índice de trabajo de Codex, AGENTS.local.md (preferencias locales), MOD-01 Identidad y acceso, MOD-02 Clientes, MOD-03 Membresías y pagos, Estados EN_TRAMITE / ACTIVO / VENCIDA, Checkout y confirmación Stripe, MOD-04 Planes y promociones (+50 more)

### Community 12 - "Landing y paginas publicas"
Cohesion: 0.04
Nodes (50): useAppResources(), Hero Banner Image (hero-banner.png), Shirtless Athlete Performing EZ-Bar Curl, Dark Low-Key Brick Wall Visual Style, Gym Landing Page Hero Section, configured, container, emit (+42 more)

### Community 13 - "Horarios por servicio"
Cohesion: 0.05
Nodes (54): activeSchedules, availableSlots(), closeEditor(), compareBase(), dayLabel(), dayOrder(), days, defaultForm() (+46 more)

### Community 14 - "Rutas de matricula y errores HTTP"
Cohesion: 0.06
Nodes (43): ConfiguracionGimnasioInput, HorarioInput, HorarioServicioInput, MatriculaHorarioInput, RegistrarClienteMembresiaInput, TicketAtencionInput, http_error(), google_auth() (+35 more)

### Community 15 - "Movimientos de inventario"
Cohesion: 0.04
Nodes (50): sortRows(), activeInventory, authStore, countByType, dateFrom, dateTo, destinationFilter, destinationOf() (+42 more)

### Community 16 - "Monitoreo de rutinas del entrenador"
Cohesion: 0.06
Nodes (37): enrollmentId, open, routineId, ex, exercises, observation, open, props (+29 more)

### Community 17 - "Contratos de repositorio"
Cohesion: 0.06
Nodes (9): apply_record(), AttendanceDomainAccess, SaveAttendanceCommand, GymCommand, GymQuery, JsonValue, GymRepository, OperationExecutor (+1 more)

### Community 18 - "Servicio de clientes"
Cohesion: 0.08
Nodes (22): ClientsService, ClienteInput, MembresiaInput, RegistroAdminClienteInput, get_client_payments_service(), activar_membresia_cliente(), confirmar_pago_manual(), confirmar_retorno_stripe() (+14 more)

### Community 19 - "Fachadas Local y Supabase"
Cohesion: 0.06
Nodes (21): LegacyGymFacade, LocalGymService, SupabaseGymService, api(), Gateway, StoreGym, test_administrative_cancel_closes_checkout_before_changing_order(), test_direct_domain_commands_also_reject_invalid_exercise_data_before_mutating_state() (+13 more)

### Community 20 - "Checkout de tienda y pagos"
Cohesion: 0.10
Nodes (25): PaymentGateway, ClientPaymentsService, confirm_verified_checkout(), _is_store_checkout(), _value(), actualizar_estado_pedido(), cancelar_checkout_tienda(), cancelar_por_sesion_expirada() (+17 more)

### Community 21 - "Matricula del cliente"
Cohesion: 0.04
Nodes (50): actionBusy, authClient, authClientId, authUser, cancelSelected(), canEnrollSelected, closeSchedulePicker(), currentClient (+42 more)

### Community 22 - "Operaciones de cuentas"
Cohesion: 0.11
Nodes (23): AuthenticateClientePasswordQuery, AuthenticateUsuarioPasswordQuery, ClientesNormalizedQuery, ClientesQuery, ConfirmarPagoClientePublicoCommand, ConfirmarPagoManualClienteCommand, DeleteClienteCommand, DeleteUsuarioCommand (+15 more)

### Community 23 - "Router y paneles por rol"
Cohesion: 0.04
Nodes (38): AdminDashboard(), AuthCallbackView(), ClientsView(), EnrollmentView(), HomeView(), InventoryView(), LandingView(), PreguntasFrecuentesView() (+30 more)

### Community 24 - "Funcion Edge de correos"
Cohesion: 0.08
Nodes (31): containsControls(), days, DeliveryContext, deliveryError(), emailAddress(), escape(), hour(), idempotencyKey() (+23 more)

### Community 25 - "Directorio de clientes"
Cohesion: 0.05
Nodes (40): clientMembershipGroup(), clientMembershipLabel(), clientNumber(), CLIENTS_PER_PAGE, filterClientDirectory(), normalize(), normalizeMembershipStatus(), paginateClients() (+32 more)

### Community 26 - "Servicio de asistencia"
Cohesion: 0.11
Nodes (20): AttendanceService, admin(), api(), attendance(), enroll(), enter(), test_capacity_is_shared_by_general_and_schedule_entries(), test_client_week_contains_only_own_general_visits() (+12 more)

### Community 27 - "Contexto de reglas de dominio"
Cohesion: 0.09
Nodes (16): AttendanceDependencies, DashboardDependencies, DashboardRules, compose_domain(), _days_until(), _now_iso(), _parse_utc(), _pedido_pagado() (+8 more)

### Community 28 - "Modulos de aplicacion frontend"
Cohesion: 0.14
Nodes (27): createAttendanceModule(), createClientsModule(), createDashboardModule(), createInventoryModule(), createMembershipsModule(), createSchedulesModule(), createStoreModule(), createSynchronizationModule() (+19 more)

### Community 29 - "Reglas de horarios"
Cohesion: 0.09
Nodes (7): SchedulesRules, _fn(), _fn(), _fn(), _fn(), _fn(), _fn()

### Community 30 - "Promociones y tema visual"
Cohesion: 0.05
Nodes (38): useThemePreferences(), app, pinia, applyTheme(), initializeTheme(), instances, themeState(), useTheme() (+30 more)

### Community 32 - "Stores de Pinia"
Cohesion: 0.10
Nodes (26): useAuth(), createGymState(), context, getApplicationServices(), instances, useAttendance(), useAuthentication(), createBackendGateway() (+18 more)

### Community 33 - "Operaciones de tienda"
Cohesion: 0.08
Nodes (14): ActualizarPedidoTiendaCommand, CancelarPedidoPagoPendienteCommand, ConfirmarPagoPedidoTiendaCommand, CrearPedidoTiendaCommand, CrearPedidoTiendaPagoPendienteCommand, DeleteProductoTiendaCommand, GetPedidoTiendaQuery, GetProductoTiendaQuery (+6 more)

### Community 34 - "Refresco remoto de Supabase"
Cohesion: 0.08
Nodes (21): test_enrollment_reads_only_its_dependencies_before_rejecting_an_unknown_client(), test_order_name_lookup_does_not_replace_an_unpublished_product_snapshot(), test_remote_summary_uses_counts_open_visits_and_eight_recent_records(), test_routine_write_ignores_unrelated_attendance_failures_and_compares_only_catalog(), rpc(), RecordingRemote, scoped_api(), service_with_remote() (+13 more)

### Community 35 - "Reglas de pagos y fechas"
Cohesion: 0.11
Nodes (39): limaTime(), addMonthsISO(), buildAttendanceRecord(), clientIdentity(), dateFromISO(), daysUntilISO(), findMemberForAttendance(), generateInventoryCode() (+31 more)

### Community 36 - "Panel de inicio"
Cohesion: 0.05
Nodes (44): weekdayFromISO(), activeMembers, adminCards, attendance, attendanceFor(), attendanceTrendData, barOptions, baseScale (+36 more)

### Community 37 - "Repositorio Supabase"
Cohesion: 0.10
Nodes (9): commit_snapshot(), table_changes(), TableMetadata, selected_resources(), _config_to_remote(), _map_config(), to_remote_body(), missing_column() (+1 more)

### Community 38 - "Configuracion y Google"
Cohesion: 0.07
Nodes (15): get_settings(), _load_env_file(), Settings, verify_google_credential(), payload(), settings(), test_missing_key_disables_notifications_and_key_is_private(), test_no_delivery_id_is_not_reported_as_sent() (+7 more)

### Community 39 - "Docker Compose"
Cohesion: 0.06
Nodes (41): VITE_APP_NAME, VITE_AUTH_API_BASE_URL, VITE_AUTH_MODE, VITE_ENABLE_DEMO_LOGIN, VITE_GOOGLE_CLIENT_ID, VITE_SUPABASE_ANON_KEY, VITE_SUPABASE_LANDING_BUCKET, VITE_SUPABASE_LANDING_FOLDER (+33 more)

### Community 40 - "Workflow de validacion de PR"
Cohesion: 0.06
Nodes (40): concurrency, cancel-in-progress, group, AUTH_SECRET_KEY, GYM_TEST_POSTGRES_CONTAINER, jobs, postgres, schedule-emails (+32 more)

### Community 41 - "Reglas de membresias"
Cohesion: 0.13
Nodes (8): MembershipsRules, _fn(), _fn(), _fn(), _fn(), _fn(), _fn(), _fn()

### Community 42 - "Operaciones de horarios"
Cohesion: 0.13
Nodes (16): AsignarRutinaMatriculaCommand, CancelarMatriculaHorarioCommand, CatalogoRutinaQuery, DeleteHorarioServicioCommand, GetHorarioServicioQuery, GetMatriculaHorarioQuery, HorariosQuery, HorariosServicioQuery (+8 more)

### Community 43 - "Operaciones de membresias"
Cohesion: 0.13
Nodes (15): ActivarMembresiaClienteCommand, CrearMembresiaCommand, DeletePlanMembresiaCommand, DeletePromocionCommand, GetPlanMembresiaQuery, GetPromocionVigenteParaPlanQuery, MembresiasPorClienteQuery, MembresiasQuery (+7 more)

### Community 44 - "Notificaciones por correo"
Cohesion: 0.11
Nodes (11): EmailSender, MembershipNotificationQueue, NotificationQueue, ScheduleNotificationQueue, MembershipNotificationService, notify_membership(), process_pending_emails(), notify_schedule_enrollment() (+3 more)

### Community 45 - "Planes y validacion de formularios"
Cohesion: 0.10
Nodes (31): ACCOUNT_EMAIL_DOMAINS, amountError(), dniError(), durationError(), EMAIL_DOMAIN_MESSAGE, emailError(), passwordError(), phoneError() (+23 more)

### Community 46 - "Componentes del repositorio"
Cohesion: 0.13
Nodes (12): GymCache, GymChangePlanner, compose_repository(), RepositoryComponents, GymSettingsRepository, GymSnapshotReader, GymTableAccess, InventoryStatusWriter (+4 more)

### Community 47 - "Navegacion de modulos"
Cohesion: 0.07
Nodes (26): createModuleLoader(), MAX_MODULE_WAIT_MS, prepareNavigationSession(), sectionForPath(), activeLink, { APP_CONFIG }, currentSectionTitle, gymStore (+18 more)

### Community 48 - "Asistencia del cliente"
Cohesion: 0.10
Nodes (31): addDays(), calendarDate(), monthWeeks(), scheduleOccurrences(), weekStart(), visibleWeek, emit, month (+23 more)

### Community 49 - "Grilla de horarios Excel"
Cohesion: 0.10
Nodes (34): agendaDays, availabilityLabel(), availableSlots(), badgeTone(), calendarEvents, calendarOptions, dayByIndex, dayLabels (+26 more)

### Community 50 - "Rutinas del entrenador"
Cohesion: 0.06
Nodes (29): averageExercisesPerRoutine, baselineSignature, currentPage, editingAssignedCount, editingName, errorMessage, exerciseErrors, gymStore (+21 more)

### Community 51 - "Reglas de cuentas"
Cohesion: 0.12
Nodes (6): AccountsRules, _fn(), _fn(), _fn(), _fn(), internal_account_active()

### Community 52 - "InventoryMovementsView.vue"
Cohesion: 0.06
Nodes (28): activeInventory, authStore, dateFrom, dateTo, errors, feedback, feedbackClass, feedbackTone (+20 more)

### Community 53 - "re"
Cohesion: 0.11
Nodes (12): civil_date(), clock_time(), date_range(), dni_number(), email_address(), identifier(), nonnegative(), phone_number() (+4 more)

### Community 54 - "StoreMovementsPanel.vue"
Cohesion: 0.07
Nodes (31): matchesSearch(), activeMovements, clientFilter, clientOptions, currentMonth, exportNotice, exportToExcel(), filteredAmount (+23 more)

### Community 55 - "Spec 000 Base implementada"
Cohesion: 0.09
Nodes (26): Estructura para Codex y Spec Kit, AGENTS.local.md configuracion personal, Skill gym-spec-driven, Perfiles revisor y auditor, Reglas por tema/ruta (.codex/rules), settings.json de .codex, Recorrido completo en un solo pedido, Flujo Spec Kit con Codex (+18 more)

### Community 56 - "SupabaseRestClient"
Cohesion: 0.11
Nodes (5): NotificationRepository, ScheduleNotificationRepository, RowsPage, SupabaseRestClient, test_count_requests_no_rows_and_preserves_filters()

### Community 57 - "Regla: Seguridad y límites de acceso"
Cohesion: 0.09
Nodes (29): Perfil Auditor, Perfiles de revisión (agents README), Perfil Revisor, reviews.analyze (perfil revisor en settings), reviews.close (perfil auditor en settings), Regla: Backend y contratos HTTP, app/bootstrap.py (conexión de adaptadores), GymService y servicios por módulo (+21 more)

### Community 58 - "attendance_routes.py"
Cohesion: 0.15
Nodes (19): AttendanceAnnulment, AttendanceCorrection, AttendanceFilters, GeneralAttendanceEntry, annul(), checkin(), checkin_dni(), correct() (+11 more)

### Community 59 - "InventoryRules"
Cohesion: 0.17
Nodes (8): InventoryRules, _fn(), _fn(), _fn(), _fn(), _fn(), _fn(), integer_quantity()

### Community 60 - "security.py"
Cohesion: 0.17
Nodes (20): create_local_token(), decode_token_payload(), get_auth_secret(), get_expiry_seconds(), get_user_role(), hash_password(), normalize_profile(), verify_password() (+12 more)

### Community 61 - "RegisterView.vue"
Cohesion: 0.08
Nodes (23): RegisterView(), activePromotions, backendPlans, defaultPlans, feedback, feedbackTone, { fieldErrors, validateField, revalidateField, validateForm }, form (+15 more)

### Community 62 - "StorePaymentView.vue"
Cohesion: 0.08
Nodes (27): cancelPayment(), cart, cartTotal, clearReturnQuery(), client, errorMessage(), feedback, feedbackClass (+19 more)

### Community 63 - "ExtensibleSelect.vue"
Cohesion: 0.10
Nodes (26): cleanText(), isAllowedText(), NAME_MAX_LENGTH, normalizeSearch(), SEARCH_MAX_LENGTH, uniqueOptions(), allOptions, confirmNew() (+18 more)

### Community 64 - "UsersView.vue"
Cohesion: 0.08
Nodes (24): UsersView(), closeEditor(), confirmDelete(), editingId, feedbackMessage, feedbackTone, feedbackToneClass, { fieldErrors, validateField, revalidateField, validateForm, resetValidation } (+16 more)

### Community 65 - "domain/errors.py"
Cohesion: 0.13
Nodes (10): AttendanceConflict, EnrollmentConflict, EntityNotFound, MembershipRequired, database_code(), error_payload(), AttendanceRepository, raise_schedule_enrollment_error() (+2 more)

### Community 66 - "StoreRules"
Cohesion: 0.15
Nodes (6): StoreRules, _fn(), _fn(), _fn(), _fn(), _fn()

### Community 68 - "StripeService"
Cohesion: 0.15
Nodes (10): StripeService, _value(), _checkout(), test_checkout_changed_parameters_do_not_reuse_key(), test_checkout_creates_hosted_stripe_session(), test_checkout_rejects_live_key_in_test_mode(), test_checkout_reports_missing_stripe_configuration(), test_checkout_requires_webhook_before_accepting_payments() (+2 more)

### Community 69 - "AttendanceHistory.vue"
Cohesion: 0.09
Nodes (25): xlsx@^0.18.5, active, annulling, apply(), { attendanceGet }, changePage(), draft, emit (+17 more)

### Community 70 - "ref_node_assert"
Cohesion: 0.13
Nodes (16): createDefaultMembership(), decodeJWT(), getUserRole(), isValidEmail(), isValidUser(), clearAuthStorage(), getAuthSession(), safeParse() (+8 more)

### Community 71 - "Guia practica chatbot con Spec Kit"
Cohesion: 0.09
Nodes (24): Entorno .specify/.venv con CLI opcional, Guia practica chatbot con Spec Kit, Chatbot de clientes (ejemplo de alcance NNN-chatbot-clientes), Criterios de ejemplo CA-01..CA-10 del chatbot, Decisiones de alcance del chatbot (audiencia, datos, proveedor, memoria, limites, fallos, acciones), Integracion del chatbot en cuatro capas, Matriz minima de pruebas del chatbot, MOD-12 contrato vivo futuro del chatbot (+16 more)

### Community 72 - "bootstrap.py"
Cohesion: 0.13
Nodes (13): create_client_payments_service(), create_gym_service(), create_identity_service(), create_membership_notifications(), create_payment_gateway(), create_schedule_notifications(), notify_membership(), notify_schedule_enrollment() (+5 more)

### Community 73 - "auth_service.py"
Cohesion: 0.19
Nodes (10): AuthService, ClientActivationRequired, ClientMembershipExpired, ClientMembershipRequired, GoogleLinkRequired, AuthGoogleRequest, AuthPasswordRequest, AuthResponse (+2 more)

### Community 74 - "gym.py"
Cohesion: 0.16
Nodes (23): AsistenciaEntradaInput, AsistenciaInput, AsistenciaSalidaInput, AsistenciaUpdateInput, CheckinAsistenciaDniInput, CheckinAsistenciaInput, EjercicioInput, EjercicioProgresoInput (+15 more)

### Community 75 - "common.sh"
Cohesion: 0.16
Nodes (22): check-prerequisites.sh script, check_dir(), check_file(), find_specify_root(), format_speckit_command(), get_current_branch(), get_feature_paths(), get_invoke_separator() (+14 more)

### Community 76 - "Preámbulo común de etapas Spec Kit"
Cohesion: 0.19
Nodes (21): Preámbulo común de etapas Spec Kit, Skill gym-spec-driven, Skill speckit-analyze, Extension hooks (.specify/extensions.yml), Skill speckit-checklist, Skill speckit-clarify, Sección Clarifications (máx. 5 preguntas), Skill speckit-constitution (+13 more)

### Community 77 - "clientIdentity.js"
Cohesion: 0.18
Nodes (21): attendanceBelongsToClient(), buildClientIdentityFromUser(), findClientForUser(), normalizeCode(), normalizeDni(), normalizeEmail(), numericFromCode(), resolveClientIdForUser() (+13 more)

### Community 78 - "utils/attendance.js"
Cohesion: 0.14
Nodes (18): limaDate(), clientBlock, dni, dniInput, props, resultBack, openVisit, props (+10 more)

### Community 79 - "MembershipPaymentsView.vue"
Cohesion: 0.09
Nodes (16): filterMembershipPayments(), searchable(), summarizeMembershipPayments(), MembershipPaymentsView(), error, filtered, filters, gymStore (+8 more)

### Community 80 - "11-schedule-enrollment.test.js"
Cohesion: 0.12
Nodes (24): activeServiceSchedules(), availableSlots(), DAY_ORDER, dayLabel(), enrollmentsForClient(), exerciseName(), formatScheduleHours(), isScheduleFull() (+16 more)

### Community 81 - "apiClient.js"
Cohesion: 0.16
Nodes (15): APP_CONFIG, apiDelete, authHeaders, createApiClient(), rawRequest, request, parseError(), parseResponse() (+7 more)

### Community 82 - "OrdersView.vue"
Cohesion: 0.10
Nodes (22): OrdersView(), canCancel(), clientOf(), ensureDraft(), feedback, filteredOrders, gymStore, isCancelled() (+14 more)

### Community 83 - "test_stripe_confirmation.py"
Cohesion: 0.16
Nodes (14): _confirm_checkout(), FakeClientsService, _install_gateway(), _paid_checkout(), test_confirm_verified_checkout_does_not_persist_unpaid_session(), test_confirm_verified_checkout_persists_paid_session(), test_confirm_verified_checkout_rejects_another_membership(), test_confirm_verified_checkout_rejects_live_session_in_test_mode() (+6 more)

### Community 84 - "operations/attendance.py"
Cohesion: 0.19
Nodes (9): ActualizarAsistenciaCommand, AsistenciaQuery, EliminarAsistenciaCommand, RegistrarAsistenciaCommand, RegistrarAsistenciaDetalladaCommand, RegistrarAsistenciaPorDniCommand, RegistrarEntradaHorarioCommand, RegistrarSalidaHorarioCommand (+1 more)

### Community 85 - "inputRules.js"
Cohesion: 0.14
Nodes (20): ALLOWED_IMAGE_MESSAGE, DEFAULT_PAGE_SIZE, IMAGE_TYPES, isAllowedImageFile(), missingFields(), missingFieldsMessage(), PAGE_SIZES, changeSize() (+12 more)

### Community 86 - "lucide-vue-next"
Cohesion: 0.09
Nodes (15): close(), dialog, emit, props, titleId, dialog, emit, props (+7 more)

### Community 87 - "Constitucion de AC Silver's GYM"
Cohesion: 0.13
Nodes (15): Constitucion de AC Silver's GYM, commit_gym_transaction RPC, context.md obligatorio antes de planificar, Siete componentes de spec (Sprint Goal, User Story, Acceptance Criteria, Technical Constraints, Guardrails, Edge Cases, Definition of Done), Constitution template, Placeholders de principios y gobierno, Context template (override), Base obligatoria del contexto (+7 more)

### Community 88 - "store_images_service.py"
Cohesion: 0.12
Nodes (5): create_store_images_service(), ImageStorage, StoreImagesService, LocalImageStorage, images_api()

### Community 89 - "test_maintainability_fixes.py"
Cohesion: 0.11
Nodes (12): validate_image(), UsuarioInput, test_database_messages_are_translated_at_the_adapter_boundary(), test_google_schema_check_preserves_connection_failures(), test_http_reports_a_late_repository_failure_as_503(), test_image_policy_accepts_only_png_and_jpg(), test_image_policy_rejects_unsupported_or_mismatched_formats(), test_image_policy_tells_which_formats_are_allowed() (+4 more)

### Community 90 - "test_admin_client_payment.py"
Cohesion: 0.10
Nodes (6): api(), test_manual_payment_endpoint_rejects_non_staff(), test_panel_rejects_non_admin_roles(), test_panel_rejects_public_and_unknown_origin(), test_panel_requires_authentication(), test_stripe_failure_keeps_registration_available_for_retry()

### Community 91 - "bootstrap.js"
Cohesion: 0.23
Nodes (12): configureApplicationServices(), installServices(), GOOGLE_CONFIG, createAttendanceRepository(), createClientsRepository(), dataRequest(), createGymSettingsRepository(), createInventoryRepository() (+4 more)

### Community 92 - "http_transport.py"
Cohesion: 0.19
Nodes (7): PersistenceUnavailable, json_request(), RemoteServiceError, send(), send_response(), supabase_headers(), SupabaseStorageService

### Community 93 - "test_module_error_control.py"
Cohesion: 0.13
Nodes (14): install_error_handlers(), invalid_input(), known_error(), _validation_detail(), test_http_reports_a_foreign_key_rejection_as_409(), api(), FailingService, test_all_modules_report_unavailable_services_without_leaking_details() (+6 more)

### Community 94 - "test_membership_expiration.py"
Cohesion: 0.13
Nodes (11): api(), expire(), gym(), test_duplicate_stripe_payment_cannot_unblock_expired_account(), test_expired_membership_cannot_be_reactivated_or_extended_through_edit(), test_expired_password_login_and_existing_signed_token_are_blocked(), test_linked_google_login_is_blocked_after_expiration(), test_new_paid_membership_can_restore_access_after_admin_activation() (+3 more)

### Community 95 - "23-layer-boundaries.test.js"
Cohesion: 0.12
Nodes (13): useClientPayments(), canPayClientWithStripe(), useClientMembershipActions(), PaymentView(), confirmationError, confirmationState, { confirmMembershipPayment }, idCliente (+5 more)

### Community 96 - "operations/inventory.py"
Cohesion: 0.22
Nodes (8): ActualizarMovimientoInventarioCommand, DeleteInventarioCommand, GetItemInventarioQuery, InventarioQuery, MovimientosInventarioQuery, RegistrarMovimientoInventarioCommand, UpsertInventarioCommand, InventoryOperations

### Community 97 - "AttendanceRules"
Cohesion: 0.24
Nodes (5): AttendanceRules, _fn(), _fn(), _fn(), _now_time()

### Community 98 - "LoginView.vue"
Cohesion: 0.11
Nodes (19): LoginView(), { authenticateWithGoogleCredential,
  authenticateWithPassword,
  loadGoogleIdentityScript, }, cancelLink(), completeLogin(), { GOOGLE_CONFIG, landingImageUrl }, googleButtonRef, googleError, googleReady (+11 more)

### Community 100 - "steps"
Cohesion: 0.10
Nodes (19): runs-on, steps, timeout-minutes, jobs, documentation, name, permissions, contents (+11 more)

### Community 101 - "test_layer_boundaries.py"
Cohesion: 0.14
Nodes (5): FakePasswords, RecordingRepository, test_client_registration_uses_injected_repository_and_hasher(), test_imports_respect_layer_boundaries(), test_persistence_does_not_inherit_domain_rules()

### Community 102 - "create_pedido_checkout()"
Cohesion: 0.13
Nodes (10): cancelar_pago_pedido(), create_pedido(), create_pedido_checkout(), _http_error(), list_pedidos(), list_producto_imagenes(), list_productos(), update_pedido() (+2 more)

### Community 103 - "test_review_regressions.py"
Cohesion: 0.18
Nodes (12): gym(), internal_account(), test_client_deletion_removes_enrollments_progress_and_releases_capacity(), test_client_edit_preserves_registration_date_across_normalization_and_mapping(), test_disabled_account_is_denied_by_login_and_protected_http_routes(), test_disabling_an_internal_account_revokes_an_existing_session(), test_editing_and_normalizing_an_internal_account_does_not_reactivate_it(), test_google_cannot_authenticate_or_link_an_inactive_internal_account() (+4 more)

### Community 105 - "attendanceService.js"
Cohesion: 0.14
Nodes (16): apiGet, apiPost, apiPut, attendanceAnnul, attendanceCorrect, attendanceEntry, attendanceExit, attendanceGet (+8 more)

### Community 106 - "AttendanceCorrectionDialog.vue"
Cohesion: 0.14
Nodes (16): actionLabels, { attendanceAnnul,
  attendanceCorrect, }, backdrop(), busy, cancel(), close(), dialog, emit (+8 more)

### Community 107 - "create-new-feature.sh"
Cohesion: 0.21
Nodes (14): Spec template (override), Siete secciones de la spec override, Spec template (upstream), Marcadores NEEDS CLARIFICATION, User stories priorizadas independientemente verificables, clean_branch_name(), contains_non_ascii(), fit_branch_name() (+6 more)

### Community 108 - "SchemaNotReady"
Cohesion: 0.17
Nodes (5): SchemaNotReady, SnapshotConflict, GymUnitOfWork, test_unit_of_work_can_retry_and_restore_state_without_a_global_repository(), commit()

### Community 109 - "backend requirements.txt"
Cohesion: 0.12
Nodes (17): backend requirements.txt, cachecontrol (dependencia runtime), backend requirements-dev.txt, flake8 (dependencia de desarrollo), httpx (dependencia de desarrollo), pytest (dependencia de desarrollo), fastapi (dependencia runtime), google-auth (dependencia runtime) (+9 more)

### Community 110 - "ProductEditorDialog.vue"
Cohesion: 0.15
Nodes (12): cleanDecimal(), isAllowedDecimal(), isAllowedInteger(), blockNameChars, blockPriceChars, cleanPrice(), props, warnings (+4 more)

### Community 111 - "services"
Cohesion: 0.12
Nodes (16): generateValue, key, sync, value, services, autoDeployTrigger, branch, buildCommand (+8 more)

### Community 112 - "test_basic_form_validation.py"
Cohesion: 0.21
Nodes (12): PlanMembresiaInput, account_email(), test_approved_account_email_is_normalized(), test_domain_commands_cannot_bypass_email_validation(), test_duplicate_accounts_fail_without_mutation_and_allow_editing_self(), test_every_account_write_schema_rejects_unapproved_domains(), test_invalid_account_requests_do_not_reach_writes_or_checkout(), test_malformed_account_email_has_an_actionable_message() (+4 more)

### Community 113 - "membership_lifecycle.py"
Cohesion: 0.23
Nodes (8): apply_membership_expiration(), _date(), membership_current(), membership_expired(), project_memberships(), _status(), command_operation(), query_operation()

### Community 114 - "operations/configuration.py"
Cohesion: 0.28
Nodes (5): ConfiguracionGimnasioQuery, SummaryQuery, TicketsQuery, UpsertTicketCommand, ConfigurationOperations

### Community 115 - "with"
Cohesion: 0.26
Nodes (15): steps, steps, steps, steps, steps, steps, if, name (+7 more)

### Community 116 - "email_templates.py"
Cohesion: 0.25
Nodes (6): _email(), email_sender(), membership_email(), schedule_email(), test_https_sender_preserves_recipient_and_updates_queued_sender(), test_templates_work_without_gmail()

### Community 117 - "mappers/store.py"
Cohesion: 0.24
Nodes (6): cents(), discounted_price(), _map_sale(), _map_sale_detail(), _sale_detail_to_remote(), _sale_to_remote()

### Community 119 - "StoreMovementsPanelView.vue"
Cohesion: 0.18
Nodes (9): activeMovements, filteredMovements, gymStore, isPaid(), movements, orderClient(), search, soldAmount (+1 more)

### Community 120 - "jobs"
Cohesion: 0.15
Nodes (12): concurrency, cancel-in-progress, group, if, needs, runs-on, timeout-minutes, jobs (+4 more)

### Community 121 - "trainer_routes.py"
Cohesion: 0.27
Nodes (9): CatalogoRutinaInput, MatriculaRutinaInput, RutinaProgresoInput, assign_trainer_rutina(), trainer_cliente_rutinas(), trainer_overview(), trainer_rutina_progreso(), upsert_trainer_rutina() (+1 more)

### Community 123 - "_schedule_service()"
Cohesion: 0.26
Nodes (4): test_week_attendance_matches_date_and_client_across_month_boundary(), _schedule_service(), ScheduleEnrollmentDomainTests, TrainerRoutineAssignmentTests

### Community 124 - "SessionProvider"
Cohesion: 0.29
Nodes (3): IdentityProvider, SessionProvider, IdentityService

### Community 125 - "publicStorage.js"
Cohesion: 0.27
Nodes (9): encodeStoragePath(), joinPath(), landingBucket, landingFolder, landingImageUrl(), publicStorageUrl(), storeBucket, storeImageUrl() (+1 more)

### Community 126 - "mappers/inventory.py"
Cohesion: 0.38
Nodes (7): _archived_field(), _inventory_move_to_remote(), _inventory_to_remote(), _map_inventory(), _map_inventory_move(), _map_product(), _product_to_remote()

### Community 127 - "vercel.json"
Cohesion: 0.20
Nodes (9): buildCommand, framework, git, deploymentEnabled, headers, installCommand, outputDirectory, rewrites (+1 more)

### Community 128 - "clientDashboard.js"
Cohesion: 0.36
Nodes (7): lastSevenPeruDays(), normalize(), peruDateKey(), summarizeDashboardClients(), clientSummary, lastSevenDays, todayKey()

### Community 129 - "ConfirmDialog.vue"
Cohesion: 0.31
Nodes (8): cancel(), confirm(), dialog, emit, handleBackdrop(), messageId, props, titleId

### Community 130 - "ResourceModal.vue"
Cohesion: 0.31
Nodes (7): emit, handleBackdropClick(), handleKeydown(), panel, pressedOnBackdrop, props, requestClose()

### Community 131 - "buildSignature()"
Cohesion: 0.28
Nodes (9): buildSignature(), closeRoutineModal(), editRoutine(), hasChanges, openCreateModal(), openModal(), parseRepeticiones(), requestCloseModal() (+1 more)

### Community 132 - "docker-ci"
Cohesion: 0.22
Nodes (9): env, if, name, runs-on, timeout-minutes, COMPOSE_PROJECT_NAME, DOCKER_CHECK_DATABASE, DOCKER_CONTAINER_PREFIX (+1 more)

### Community 133 - "exportCsv()"
Cohesion: 0.25
Nodes (8): baseFiltered, dateInRange(), exportCsv(), itemId(), itemName(), movementLabel(), selectedItem, userName()

### Community 134 - "norm()"
Cohesion: 0.25
Nodes (8): activeServicesCount, errors, exerciseCount(), filteredRoutines, norm(), routinesForService(), toggleZone(), zoneActive()

### Community 135 - "buildPayload()"
Cohesion: 0.25
Nodes (8): buildExercise(), buildPayload(), buildRepString(), refresh(), saveRoutine(), setRepMode(), showToast(), syncRepString()

### Community 136 - "deploy-vercel"
Cohesion: 0.25
Nodes (8): env, needs, runs-on, timeout-minutes, VERCEL_ORG_ID, VERCEL_PROJECT_ID, VERCEL_TOKEN, deploy-vercel

### Community 137 - "Tasks template (override)"
Cohesion: 0.29
Nodes (6): Tasks template (override), Cierre con hook --stage close, Formato de tarea TNNN [USn] con CA-NN, Tasks template (upstream), Fases Setup/Foundational/User Stories/Polish, Marcador [P] de tareas paralelas

### Community 139 - "rickroll.gif (Rick Astley 'Never Gonna G"
Cohesion: 0.33
Nodes (6): rickroll.gif (Rick Astley 'Never Gonna Give You Up' meme GIF), Rickroll Meme / Easter Egg, tp-remix Asset Group (frontend presentation assets), tenor-meme.gif (TP Remix meme asset), Red-armored tokusatsu hero (likely Kamen Rider Kuuga) meme GIF, TP Remix easter-egg / decorative meme media

### Community 140 - "SortableTh.vue"
Cohesion: 0.29
Nodes (6): ariaSort, emit, icon, isActive, props, title

### Community 141 - "deploy-render"
Cohesion: 0.29
Nodes (7): env, needs, runs-on, timeout-minutes, DEPLOY_SHA, RENDER_DEPLOY_HOOK_URL, deploy-render

### Community 142 - "interface"
Cohesion: 0.29
Nodes (6): interface, default_prompt, display_name, short_description, policy, allow_implicit_invocation

### Community 143 - "validate.py (hook de validación)"
Cohesion: 0.40
Nodes (5): Hook único de validación (README), Etapas del hook: plan, implement, close, validate.py (hook de validación), Regla: Pruebas y evidencia, Comandos de verificación por área (pytest, npm test, deno, validate.py)

### Community 145 - "PromocionInput"
Cohesion: 0.40
Nodes (3): PromocionInput, update_promocion(), upsert_promocion()

### Community 149 - "frontend index.html"
Cohesion: 0.40
Nodes (5): frontend index.html, #app mount point, Font Awesome 6.5.1 (cdnjs), Google Fonts Anton y Manrope, /src/main.js module entry

### Community 150 - "backend-ci"
Cohesion: 0.40
Nodes (5): if, needs, runs-on, timeout-minutes, backend-ci

### Community 151 - "schedule-emails-ci"
Cohesion: 0.40
Nodes (5): schedule-emails-ci, if, needs, runs-on, timeout-minutes

### Community 153 - "favicon.svg (Vite lightning-bolt logo)"
Cohesion: 0.67
Nodes (4): favicon.svg (Vite lightning-bolt logo), Gaussian Blur Glow Filters (b-p), Lightning Bolt Path with Alpha Mask, Vite Brand Logo (default scaffold icon)

### Community 154 - "pull_request"
Cohesion: 0.50
Nodes (4): branches, types, True, pull_request

### Community 155 - "Release 1.1.0 MVP (2026-09-15)"
Cohesion: 0.67
Nodes (3): CHANGELOG, CI habilitado para Git Flow y tags de version, Release 1.1.0 MVP (2026-09-15)

## Ambiguous Edges - Review These
- `Rickroll Meme / Easter Egg` → `tp-remix Asset Group (frontend presentation assets)`  [AMBIGUOUS]
  frontend/src/presentation/assets/tp-remix/rickroll.gif · relation: conceptually_related_to
- `Red-armored tokusatsu hero (likely Kamen Rider Kuuga) meme GIF` → `tenor-meme.gif (TP Remix meme asset)`  [AMBIGUOUS]
  frontend/src/presentation/assets/tp-remix/tenor-meme.gif · relation: references

## Knowledge Gaps
- **72 isolated node(s):** `Red-armored tokusatsu hero (likely Kamen Rider Kuuga) meme GIF`, `TP Remix easter-egg / decorative meme media`, `Vite Brand Logo (default scaffold icon)`, `Shirtless Athlete Performing EZ-Bar Curl`, `cachecontrol (dependencia runtime)` (+67 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 1550 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **33 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `GymService` connect `Fachada GymService` to `Contratos PostgreSQL y validador`, `Rutas y arranque FastAPI`, `Pruebas de prioridad y alcance`, `Rutas de matricula y errores HTTP`, `.__init__()`, `PromocionInput`, `Servicio de clientes`, `Fachadas Local y Supabase`, `Checkout de tienda y pagos`, `Servicio de asistencia`, `Reglas de horarios`, `Refresco remoto de Supabase`, `bootstrap.py`, `auth_service.py`, `test_maintainability_fixes.py`, `test_layer_boundaries.py`, `create_pedido_checkout()`, `test_review_regressions.py`, `trainer_routes.py`?**
  _High betweenness centrality (0.050) - this node is a cross-community bridge._
- **Are the 73 inferred relationships involving `GymService` (e.g. with `health()` and `AuthService`) actually correct?**
  _`GymService` has 73 INFERRED edges - model-reasoned connections that need verification._
- **What connects `Red-armored tokusatsu hero (likely Kamen Rider Kuuga) meme GIF`, `TP Remix easter-egg / decorative meme media`, `Vite Brand Logo (default scaffold icon)` to the rest of the system?**
  _72 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Fachada GymService` be split into smaller, more focused modules?**
  _Cohesion score 0.049959049959049956 - nodes in this community are weakly interconnected._
- **Why does `GymDomainService` connect `Agregado GymDomainService` to `Mappers de Supabase`, `Contratos de repositorio`, `._parse_cliente_id()`, `Contexto de reglas de dominio`, `Metodos del dominio legado`, `._actualizar_estados_tienda()`, `._latest_membership_for_cliente()`, `._normalize_day()`, `._resolve_cliente_for_attendance()`, `Repositorio Supabase`, `test_promocion_cupos.py`, `Componentes del repositorio`, `InventoryRules`, `domain/errors.py`, `StoreRules`, `SupabaseGymRepository`, `MemoryGymRepository`, `membership_lifecycle.py`, `._normalize()`, `.cache()`?**
  _High betweenness centrality (0.048) - this node is a cross-community bridge._

### Low-confidence Hints
_AMBIGUOUS edges — the extractor was unsure. Verify before acting on these._

- **What is the exact relationship between `Rickroll Meme / Easter Egg` and `tp-remix Asset Group (frontend presentation assets)`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **What is the exact relationship between `Red-armored tokusatsu hero (likely Kamen Rider Kuuga) meme GIF` and `tenor-meme.gif (TP Remix meme asset)`?**
  _Edge tagged AMBIGUOUS (relation: references) - confidence is low._
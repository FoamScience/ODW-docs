---
api_tags:
- class
categories:
- api
- testlib API
contributors:
- Elwardi
date: '2025-05-05'
description: API documentation for childOpenFOAMModel
foamCD:
  ctors:
  - access: public
    definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/childOpenFOAMModel/childOpenFOAMModel.H#L24-L24
    documentation:
      deprecated: ''
      description: Construct from dictionary
      returns: ''
      since: ''
    is_const: false
    is_constructor: true
    is_defaulted: false
    is_deleted: false
    is_deprecated: 0
    is_destructor: false
    is_final: false
    is_noexcept: false
    is_override: false
    is_pure_virtual: false
    is_static: false
    is_virtual: false
    name: childOpenFOAMModel<T>
    parameters: []
    return_type: null
    signature: explicit childOpenFOAMModel(const dictionary& dict)
  - access: public
    definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/childOpenFOAMModel/childOpenFOAMModel.H#L27-L27
    documentation:
      deprecated: ''
      description: Delete move construct
      returns: ''
      since: ''
    is_const: false
    is_constructor: true
    is_defaulted: false
    is_deleted: true
    is_deprecated: 0
    is_destructor: false
    is_final: false
    is_noexcept: false
    is_override: false
    is_pure_virtual: false
    is_static: false
    is_virtual: false
    name: childOpenFOAMModel<T>
    parameters: []
    return_type: null
    signature: childOpenFOAMModel(childOpenFOAMModel&& other) = delete
  - access: public
    definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/childOpenFOAMModel/childOpenFOAMModel.H#L30-L30
    documentation:
      deprecated: ''
      description: Delete default copy construct
      returns: ''
      since: ''
    is_const: false
    is_constructor: true
    is_defaulted: false
    is_deleted: true
    is_deprecated: 0
    is_destructor: false
    is_final: false
    is_noexcept: false
    is_override: false
    is_pure_virtual: false
    is_static: false
    is_virtual: false
    name: childOpenFOAMModel<T>
    parameters: []
    return_type: null
    signature: childOpenFOAMModel(const childOpenFOAMModel& other) = delete
  documentation:
    deprecated: ''
    description: ''
    is_deprecated: false
    params: {}
    returns: ''
    since: ''
  dtor:
    access: public
    definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/childOpenFOAMModel/childOpenFOAMModel.H#L33-L33
    documentation:
      deprecated: ''
      description: Destruct childOpenFOAMModels
      returns: ''
      since: ''
    is_const: false
    is_constructor: false
    is_defaulted: false
    is_deleted: false
    is_deprecated: 0
    is_destructor: true
    is_final: false
    is_noexcept: false
    is_override: false
    is_pure_virtual: false
    is_static: false
    is_virtual: false
    name: ~childOpenFOAMModel<T>
    parameters: []
    return_type: null
    signature: virtual ~childOpenFOAMModel()
  enclosed_entities: []
  factory_methods: []
  fields:
    private: []
    protected: []
    public: []
  filename: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/childOpenFOAMModel/childOpenFOAMModel.H#L10-L48
  interface:
    abstract_in_base_methods: []
    abstract_methods: []
    public_bases:
    - depth: 1
      is_direct: true
      name: OpenFOAMModel
      namespace: Foam
      public_methods: []
      uuid: a6d5abcc314575c045a14f0efcf972ba52203e923e0feabe857d96379193b7c3
    public_methods:
    - access: public
      name: type
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/childOpenFOAMModel/childOpenFOAMModel.H#L21-L21
        documentation:
          deprecated: ''
          description: Runtime type name
          returns: ''
          since: ''
        is_const: false
        is_constructor: false
        is_defaulted: 0
        is_deleted: false
        is_deprecated: 0
        is_destructor: false
        is_final: 0
        is_noexcept: false
        is_override: 0
        is_pure_virtual: 0
        is_static: 0
        is_virtual: 1
        name: type
        parameters: []
        return_type: void
        signature: virtual void type()
    - access: public
      name: clone
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/childOpenFOAMModel/childOpenFOAMModel.H#L36-L36
        documentation:
          deprecated: ''
          description: A dynamic clone of this model
          returns: A dynamic clone of this model
          since: ''
        is_const: false
        is_constructor: false
        is_defaulted: 0
        is_deleted: false
        is_deprecated: 0
        is_destructor: false
        is_final: 0
        is_noexcept: false
        is_override: 0
        is_pure_virtual: 0
        is_static: 0
        is_virtual: 1
        name: clone
        parameters: []
        return_type: void
        signature: virtual autoPtr<OpenFOAMModel<T>> clone() const
    - access: public
      name: verifyType
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/childOpenFOAMModel/childOpenFOAMModel.H#L39-L41
        documentation:
          deprecated: ''
          description: the typename
          returns: the typename
          since: ''
        is_const: false
        is_constructor: false
        is_defaulted: 0
        is_deleted: false
        is_deprecated: 0
        is_destructor: false
        is_final: 0
        is_noexcept: false
        is_override: 0
        is_pure_virtual: 0
        is_static: 0
        is_virtual: 1
        name: verifyType
        parameters: []
        return_type: void
        signature: virtual word verifyType() const
    - access: public
      name: operator=
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/childOpenFOAMModel/childOpenFOAMModel.H#L44-L44
        documentation:
          deprecated: ''
          description: Deleted move assignment
          returns: ''
          since: ''
        is_const: false
        is_constructor: false
        is_defaulted: 0
        is_deleted: 1
        is_deprecated: 0
        is_destructor: false
        is_final: 0
        is_noexcept: false
        is_override: 0
        is_pure_virtual: 0
        is_static: 0
        is_virtual: 0
        name: operator=
        parameters: []
        return_type: void
        signature: childOpenFOAMModel& operator=(childOpenFOAMModel&& other) = delete
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/childOpenFOAMModel/childOpenFOAMModel.H#L47-L47
        documentation:
          deprecated: ''
          description: Deleted copy assignment
          returns: ''
          since: ''
        is_const: false
        is_constructor: false
        is_defaulted: 0
        is_deleted: 1
        is_deprecated: 0
        is_destructor: false
        is_final: 0
        is_noexcept: false
        is_override: 0
        is_pure_virtual: 0
        is_static: 0
        is_virtual: 0
        name: operator=
        parameters: []
        return_type: void
        signature: childOpenFOAMModel& operator=(const childOpenFOAMModel& other)
          = delete
    static_methods:
    - name: typeName_
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/childOpenFOAMModel/childOpenFOAMModel.H#L21-L21
        documentation:
          deprecated: ''
          description: Runtime type name
          returns: ''
          since: ''
        is_const: false
        is_constructor: false
        is_defaulted: 0
        is_deleted: false
        is_deprecated: 0
        is_destructor: false
        is_final: 0
        is_noexcept: false
        is_override: 0
        is_pure_virtual: 0
        is_static: 1
        is_virtual: 0
        name: typeName_
        parameters: []
        return_type: void
        signature: static void typeName_()
  knowledge_requirements:
  - classes
  - default_delete
  - explicit_conversion
  - nullptr
  - openfoam_basics
  - operator_overloading
  - rvalue_references
  - templates
  member_type_aliases:
    private: []
    protected: []
    public: []
  mpi_comms:
    handles_member_reference_through_mpi: false
    has_member_reference: false
    linked_lists: false
    parallel_streams: false
    random_access_lists: false
  namespace: Foam
  openfoam_dsl:
    RTS:
      RTS_table_names: []
      base_RTS_classes: []
      class_role: unknown
      is_RTS_base: false
      is_RTS_child: false
      plugin_active: true
      rts_status: partial
    reflection:
      is_reflectable: false
      reflection_error: ''
      reflection_type: ''
      standard_config: ''
      standard_config_details: ''
  private_bases: []
  private_methods: []
  protected_bases: []
  protected_methods: []
  signature: 'template<class T>

    class childOpenFOAMModel : public OpenFOAMModel<T>'
  standard_config: ''
  unit_tests: []
layout: class
title: childOpenFOAMModel
url: /api/Foam_childOpenFOAMModel
weight: 20
---
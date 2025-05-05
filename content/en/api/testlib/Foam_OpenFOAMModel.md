---
api_tags:
- class
categories:
- api
- testlib API
contributors:
- Elwardi
date: '2025-05-05'
description: API documentation for OpenFOAMModel
foamCD:
  ctors:
  - access: public
    definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/OpenFOAMModel/OpenFOAMModel.H#L51-L51
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
    name: OpenFOAMModel<T>
    parameters: []
    return_type: null
    signature: explicit OpenFOAMModel(const dictionary& dict)
  - access: public
    definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/OpenFOAMModel/OpenFOAMModel.H#L54-L54
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
    name: OpenFOAMModel<T>
    parameters: []
    return_type: null
    signature: OpenFOAMModel(OpenFOAMModel&& other) = delete
  - access: public
    definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/OpenFOAMModel/OpenFOAMModel.H#L57-L57
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
    name: OpenFOAMModel<T>
    parameters: []
    return_type: null
    signature: OpenFOAMModel(const OpenFOAMModel& other) = delete
  documentation:
    deprecated: ''
    description: ''
    is_deprecated: false
    params: {}
    returns: ''
    since: ''
  dtor:
    access: public
    definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/OpenFOAMModel/OpenFOAMModel.H#L60-L60
    documentation:
      deprecated: ''
      description: Destruct OpenFOAMModels
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
    name: ~OpenFOAMModel<T>
    parameters: []
    return_type: null
    signature: virtual ~OpenFOAMModel()
  enclosed_entities: []
  factory_methods:
  - name: New
    overloads:
    - access: public
      definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/OpenFOAMModel/OpenFOAMModel.H#L70-L70
      documentation:
        deprecated: ''
        description: 'The concrete model from dictionary

          as a pointer to base type'
        returns: 'The concrete model from dictionary

          as a pointer to base type'
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
      name: New
      parameters: []
      return_type: void
      signature: static autoPtr<OpenFOAMModel> New(const dictionary& dict)
  fields:
    private: []
    protected: []
    public: []
  filename: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/OpenFOAMModel/OpenFOAMModel.H#L18-L89
  interface:
    abstract_in_base_methods: []
    abstract_methods:
    - name: clone
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/OpenFOAMModel/OpenFOAMModel.H#L63-L63
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
        is_pure_virtual: 1
        is_static: 0
        is_virtual: 1
        name: clone
        parameters: []
        return_type: void
        signature: virtual autoPtr<OpenFOAMModel> clone() const = 0
    - name: verifyType
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/OpenFOAMModel/OpenFOAMModel.H#L66-L66
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
        is_pure_virtual: 1
        is_static: 0
        is_virtual: 1
        name: verifyType
        parameters: []
        return_type: void
        signature: virtual word verifyType() const = 0
    public_bases: []
    public_methods:
    - access: public
      name: type
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/OpenFOAMModel/OpenFOAMModel.H#L41-L41
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
      name: dict
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/OpenFOAMModel/OpenFOAMModel.H#L73-L76
        documentation:
          deprecated: ''
          description: the configuration dictionary
          returns: the configuration dictionary
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
        is_virtual: 0
        name: dict
        parameters: []
        return_type: void
        signature: const dictionary& dict() const
    - access: public
      name: m
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/OpenFOAMModel/OpenFOAMModel.H#L79-L82
        documentation:
          deprecated: ''
          description: m member data
          returns: m member data
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
        is_virtual: 0
        name: m
        parameters: []
        return_type: void
        signature: T m() const
    - access: public
      name: operator=
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/OpenFOAMModel/OpenFOAMModel.H#L85-L85
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
        signature: OpenFOAMModel& operator=(OpenFOAMModel&& other) = delete
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/OpenFOAMModel/OpenFOAMModel.H#L88-L88
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
        signature: OpenFOAMModel& operator=(const OpenFOAMModel& other) = delete
    static_methods:
    - name: typeName_
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl0Support/OpenFOAMModel/OpenFOAMModel.H#L41-L41
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
  - openfoam_basics
  - operator_overloading
  - rvalue_references
  - templates
  member_type_aliases:
    private: []
    protected: []
    public:
    - access_specifier: public
      doc_comment: ''
      end_line: 48
      file: /api/Foam_dictionaryConstructorCompatTableType
      id: 181
      line: 44
      name: dictionaryConstructorCompatTableType
      underlying_type: ::Foam::HashTable<std::pair< ::Foam::word, int>, ::Foam::word,
        ::Foam::Hash< ::Foam::word>>
    - access_specifier: public
      doc_comment: ''
      end_line: 44
      file: /api/Foam_dictionaryConstructorPtr
      id: 179
      line: 44
      name: dictionaryConstructorPtr
      underlying_type: autoPtr<OpenFOAMModel<T>> (*)(const dictionary &)
    - access_specifier: public
      doc_comment: ''
      end_line: 48
      file: /api/Foam_dictionaryConstructorTableType
      id: 180
      line: 44
      name: dictionaryConstructorTableType
      underlying_type: ::Foam::HashTable<dictionaryConstructorPtr, ::Foam::word, ::Foam::Hash<
        ::Foam::word>>
  mpi_comms:
    handles_member_reference_through_mpi: false
    has_member_reference: false
    linked_lists: false
    parallel_streams: false
    random_access_lists: false
  namespace: Foam
  openfoam_dsl:
    RTS:
      RTS_table_names:
      - dictionary
      RTS_table_types:
      - autoPtr
      base_RTS_classes: []
      class_role: base
      is_RTS_base: true
      is_RTS_child: false
      plugin_active: true
      rts_status: complete
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

    class OpenFOAMModel'
  standard_config: ''
  unit_tests: []
layout: class
title: OpenFOAMModel
url: /api/Foam_OpenFOAMModel
weight: 20
---
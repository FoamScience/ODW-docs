---
api_tags:
- class
categories:
- api
- testlib API
contributors:
- Elwardi
date: '2025-05-05'
description: 'Base class mimiking a standard OpenFOAM model

  while having minimal dependencies but default-constructing

  most of its members'
foamCD:
  ctors:
  - access: public
    definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl1Support/basicReflectedModel/basicReflectedModel.H#L56-L56
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
    name: basicReflectedModel
    parameters: []
    return_type: null
    signature: explicit basicReflectedModel(const dictionary& dict)
  - access: public
    definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl1Support/basicReflectedModel/basicReflectedModel.H#L59-L59
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
    name: basicReflectedModel
    parameters: []
    return_type: null
    signature: basicReflectedModel(basicReflectedModel&& other) = delete
  - access: public
    definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl1Support/basicReflectedModel/basicReflectedModel.H#L62-L62
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
    name: basicReflectedModel
    parameters: []
    return_type: null
    signature: basicReflectedModel(const basicReflectedModel& other) = delete
  documentation:
    deprecated: ''
    description: 'Base class mimiking a standard OpenFOAM model

      while having minimal dependencies but default-constructing

      most of its members'
    is_deprecated: false
    params: {}
    returns: ''
    since: ''
  dtor:
    access: public
    definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl1Support/basicReflectedModel/basicReflectedModel.H#L65-L65
    documentation:
      deprecated: ''
      description: Destruct basicReflectedModels
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
    name: ~basicReflectedModel
    parameters: []
    return_type: null
    signature: virtual ~basicReflectedModel()
  enclosed_entities: []
  factory_methods:
  - name: New
    overloads:
    - access: public
      definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl1Support/basicReflectedModel/basicReflectedModel.H#L75-L75
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
      signature: static autoPtr<basicReflectedModel> New(const dictionary& dict)
  fields:
    private: []
    protected: []
    public: []
  filename: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl1Support/basicReflectedModel/basicReflectedModel.H#L18-L97
  interface:
    abstract_in_base_methods: []
    abstract_methods:
    - name: clone
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl1Support/basicReflectedModel/basicReflectedModel.H#L68-L68
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
        signature: virtual autoPtr<basicReflectedModel> clone() const = 0
    - name: verifyType
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl1Support/basicReflectedModel/basicReflectedModel.H#L71-L71
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
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl1Support/basicReflectedModel/basicReflectedModel.H#L40-L40
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
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl1Support/basicReflectedModel/basicReflectedModel.H#L78-L81
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
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl1Support/basicReflectedModel/basicReflectedModel.H#L84-L87
        documentation:
          deprecated: ''
          description: m
          returns: m
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
        signature: label m() const
    - access: public
      name: operator=
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl1Support/basicReflectedModel/basicReflectedModel.H#L90-L90
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
        signature: basicReflectedModel& operator=(basicReflectedModel&& other) = delete
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl1Support/basicReflectedModel/basicReflectedModel.H#L93-L93
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
        signature: basicReflectedModel& operator=(const basicReflectedModel& other)
          = delete
    static_methods:
    - name: typeName_
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl1Support/basicReflectedModel/basicReflectedModel.H#L40-L40
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
    - name: constructSchemaTables
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl1Support/basicReflectedModel/basicReflectedModel.H#L53-L53
        documentation:
          deprecated: ''
          description: Schema table for basicReflectedModels
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
        name: constructSchemaTables
        parameters: []
        return_type: void
        signature: static void constructSchemaTables()
    - name: destroySchemaTables
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl1Support/basicReflectedModel/basicReflectedModel.H#L53-L53
        documentation:
          deprecated: ''
          description: Schema table for basicReflectedModels
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
        name: destroySchemaTables
        parameters: []
        return_type: void
        signature: static void destroySchemaTables()
  knowledge_requirements:
  - classes
  - default_delete
  - explicit_conversion
  - openfoam_basics
  - openfoam_reflections
  - operator_overloading
  - rvalue_references
  member_type_aliases:
    private: []
    protected: []
    public:
    - access_specifier: public
      doc_comment: ''
      end_line: 47
      file: /api/Foam_dictionaryConstructorCompatTableType
      id: 142
      line: 43
      name: dictionaryConstructorCompatTableType
      underlying_type: ::Foam::HashTable<std::pair< ::Foam::word, int>, ::Foam::word,
        ::Foam::Hash< ::Foam::word>>
    - access_specifier: public
      doc_comment: ''
      end_line: 43
      file: /api/Foam_dictionaryConstructorPtr
      id: 140
      line: 43
      name: dictionaryConstructorPtr
      underlying_type: autoPtr<basicReflectedModel> (*)(const dictionary &)
    - access_specifier: public
      doc_comment: ''
      end_line: 47
      file: /api/Foam_dictionaryConstructorTableType
      id: 141
      line: 43
      name: dictionaryConstructorTableType
      underlying_type: ::Foam::HashTable<dictionaryConstructorPtr, ::Foam::word, ::Foam::Hash<
        ::Foam::word>>
    - access_specifier: public
      doc_comment: ''
      end_line: 53
      file: /api/Foam_schemaBuilderPtr
      id: 143
      line: 53
      name: schemaBuilderPtr
      underlying_type: class Foam::dictionary
    - access_specifier: public
      doc_comment: ''
      end_line: 53
      file: /api/Foam_schemaTable
      id: 144
      line: 53
      name: schemaTable
      underlying_type: Foam::basicReflectedModel::schemaBuilderPtr
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
  signature: class basicReflectedModel
  standard_config: ''
  unit_tests: []
layout: class
title: basicReflectedModel
url: /api/Foam_basicReflectedModel
weight: 20
---
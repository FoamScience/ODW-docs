---
api_tags:
- class
categories:
- api
- testlib API
contributors:
- Elwardi
date: '2025-05-05'
description: Base class taking advantage of uiElements
foamCD:
  ctors:
  - access: public
    definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L76-L76
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
    name: fullReflectedModel
    parameters: []
    return_type: null
    signature: explicit fullReflectedModel(const dictionary& dict)
  - access: public
    definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L79-L79
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
    name: fullReflectedModel
    parameters: []
    return_type: null
    signature: fullReflectedModel(fullReflectedModel&& other) = delete
  - access: public
    definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L82-L82
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
    name: fullReflectedModel
    parameters: []
    return_type: null
    signature: fullReflectedModel(const fullReflectedModel& other) = delete
  documentation:
    deprecated: ''
    description: Base class taking advantage of uiElements
    is_deprecated: false
    params: {}
    returns: ''
    since: ''
  dtor:
    access: public
    definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L85-L85
    documentation:
      deprecated: ''
      description: Destruct fullReflectedModels
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
    name: ~fullReflectedModel
    parameters: []
    return_type: null
    signature: virtual ~fullReflectedModel()
  enclosed_entities: []
  factory_methods:
  - name: New
    overloads:
    - access: public
      definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L95-L95
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
      signature: static autoPtr<fullReflectedModel> New(const dictionary& dict)
  fields:
    private: []
    protected: []
    public: []
  filename: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L19-L129
  interface:
    abstract_in_base_methods: []
    abstract_methods:
    - name: clone
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L88-L88
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
        signature: virtual autoPtr<fullReflectedModel> clone() const = 0
    - name: verifyType
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L91-L91
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
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L60-L60
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
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L98-L101
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
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L104-L107
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
      name: ht
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L110-L113
        documentation:
          deprecated: ''
          description: ht
          returns: ht
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
        name: ht
        parameters: []
        return_type: void
        signature: HashTable<word> ht() const
    - access: public
      name: dir
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L116-L119
        documentation:
          deprecated: ''
          description: dir
          returns: dir
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
        name: dir
        parameters: []
        return_type: void
        signature: vector dir() const
    - access: public
      name: operator=
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L122-L122
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
        signature: fullReflectedModel& operator=(fullReflectedModel&& other) = delete
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L125-L125
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
        signature: fullReflectedModel& operator=(const fullReflectedModel& other)
          = delete
    static_methods:
    - name: typeName_
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L60-L60
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
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L73-L73
        documentation:
          deprecated: ''
          description: Schema table for fullReflectedModels
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
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L73-L73
        documentation:
          deprecated: ''
          description: Schema table for fullReflectedModels
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
  - nullptr
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
      end_line: 67
      file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L63-L67
      id: 176
      line: 63
      name: dictionaryConstructorCompatTableType
      underlying_type: ::Foam::HashTable<std::pair< ::Foam::word, int>, ::Foam::word,
        ::Foam::Hash< ::Foam::word>>
    - access_specifier: public
      doc_comment: ''
      end_line: 63
      file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L63-L63
      id: 174
      line: 63
      name: dictionaryConstructorPtr
      underlying_type: autoPtr<fullReflectedModel> (*)(const dictionary &)
    - access_specifier: public
      doc_comment: ''
      end_line: 67
      file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L63-L67
      id: 175
      line: 63
      name: dictionaryConstructorTableType
      underlying_type: ::Foam::HashTable<dictionaryConstructorPtr, ::Foam::word, ::Foam::Hash<
        ::Foam::word>>
    - access_specifier: public
      doc_comment: ''
      end_line: 73
      file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L73-L73
      id: 177
      line: 73
      name: schemaBuilderPtr
      underlying_type: class Foam::dictionary
    - access_specifier: public
      doc_comment: ''
      end_line: 73
      file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/fullReflectedModel/fullReflectedModel.H#L73-L73
      id: 178
      line: 73
      name: schemaTable
      underlying_type: Foam::fullReflectedModel::schemaBuilderPtr
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
  signature: class fullReflectedModel
  standard_config: ''
  unit_tests: []
layout: class
title: fullReflectedModel
url: /api/Foam_fullReflectedModel
weight: 20
---
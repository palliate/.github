---
title: toml
summary: The root namespace for all toml++ functions and types. 
parent: Namespaces
grand_parent: libpalliate
layout: default
---

# toml

The root namespace for all toml++ functions and types. 

## Functions

|                | Name           |
| -------------- | -------------- |
| | **[CHECK_NODE_TYPE_MAPPING](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-type-mapping)**(int64_t , node_type::integer ) |
| | **[CHECK_NODE_TYPE_MAPPING](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-type-mapping)**(double , node_type::floating_point ) |
| | **[CHECK_NODE_TYPE_MAPPING](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-type-mapping)**(std::string , node_type::string ) |
| | **[CHECK_NODE_TYPE_MAPPING](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-type-mapping)**(bool , node_type::boolean ) |
| | **[CHECK_NODE_TYPE_MAPPING](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-type-mapping)**(toml::date , node_type::date ) |
| | **[CHECK_NODE_TYPE_MAPPING](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-type-mapping)**(toml::time , node_type::time ) |
| | **[CHECK_NODE_TYPE_MAPPING](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-type-mapping)**(toml::date_time , node_type::date_time ) |
| | **[CHECK_NODE_TYPE_MAPPING](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-type-mapping)**(toml::array , node_type::array ) |
| | **[CHECK_NODE_TYPE_MAPPING](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-type-mapping)**(toml::table , node_type::table ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**([time](/libpalliate/generated/Classes/structtime) , true ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(date , true ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**([date_time](/libpalliate/generated/Classes/structdate__time) , true ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(bool , true ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(int8_t , false ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(int16_t , false ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(int32_t , false ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(int64_t , true ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(uint8_t , false ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(uint16_t , false ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(uint32_t , false ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(uint64_t , false ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(float , false ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(double , true ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(char * , false ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(char [2], false ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(char(&) [2], false ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(const  char(&)[2], false ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(char(&&) [2], false ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(const  char(&&)[2], false ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(const char * , true ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(std::string , true ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(std::string_view , true ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(wchar_t * , false ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(wchar_t wchar_t[2], false ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(wchar_t(&) [2], false ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(const  wchar_t(&)[2], false ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(wchar_t(&&) [2], false ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(const  wchar_t(&&)[2], false ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(const wchar_t * , false ) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(std::wstring , !! TOML_ENABLE_WINDOWS_COMPAT) |
| | **[CHECK_CAN_REPRESENT_NATIVE](/libpalliate/generated/Namespaces/namespacetoml#function-check-can-represent-native)**(std::wstring_view , false ) |
| | **[CHECK_VALUE_EXACT](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-exact)**([time](/libpalliate/generated/Classes/structtime) , [time](/libpalliate/generated/Classes/structtime) ) |
| | **[CHECK_VALUE_EXACT](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-exact)**(date , date ) |
| | **[CHECK_VALUE_EXACT](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-exact)**([date_time](/libpalliate/generated/Classes/structdate__time) , [date_time](/libpalliate/generated/Classes/structdate__time) ) |
| | **[CHECK_VALUE_EXACT](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-exact)**(bool , bool ) |
| | **[CHECK_VALUE_EXACT](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-exact)**(double , double ) |
| | **[CHECK_VALUE_EXACT](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-exact)**(int64_t , int64_t ) |
| | **[CHECK_VALUE_EXACT](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-exact)**(const char * , const char * ) |
| | **[CHECK_VALUE_EXACT](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-exact)**(std::string_view , std::string_view ) |
| | **[CHECK_VALUE_EXACT](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-exact)**(std::string , std::string ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**([time](/libpalliate/generated/Classes/structtime) , [time](/libpalliate/generated/Classes/structtime) ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**([time](/libpalliate/generated/Classes/structtime) & , [time](/libpalliate/generated/Classes/structtime) ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**([time](/libpalliate/generated/Classes/structtime) && , [time](/libpalliate/generated/Classes/structtime) ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(date , date ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(date & , date ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(date && , date ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**([date_time](/libpalliate/generated/Classes/structdate__time) , [date_time](/libpalliate/generated/Classes/structdate__time) ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**([date_time](/libpalliate/generated/Classes/structdate__time) & , [date_time](/libpalliate/generated/Classes/structdate__time) ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**([date_time](/libpalliate/generated/Classes/structdate__time) && , [date_time](/libpalliate/generated/Classes/structdate__time) ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(bool , bool ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(bool & , bool ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(bool && , bool ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(int32_t , int32_t ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(int32_t & , int32_t ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(int32_t && , int32_t ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(int64_t , int64_t ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(int64_t & , int64_t ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(int64_t && , int64_t ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(float , float ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(float & , float ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(float && , float ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(double , double ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(double & , double ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(double && , double ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(char * , const char * ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(char *& , const char * ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(char *&& , const char * ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(char [2], const char * ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(char(&) [2], const char * ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(char(&&) [2], const char * ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(const char * , const char * ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(const char *& , const char * ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(const char *&& , const char * ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(const  char(&)[2], const char * ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(const  char(&&)[2], const char * ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(std::string_view , std::string_view ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(std::string_view & , std::string_view ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(std::string_view && , std::string_view ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(const std::string_view & , std::string_view ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(const std::string_view && , std::string_view ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(std::string , std::string ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(std::string & , std::string ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(std::string && , std::string ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(const std::string & , std::string ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(const std::string && , std::string ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(wchar_t * , std::wstring ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(wchar_t *& , std::wstring ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(wchar_t *&& , std::wstring ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(wchar_t wchar_t[2], std::wstring ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(wchar_t(&) [2], std::wstring ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(wchar_t(&&) [2], std::wstring ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(const wchar_t * , std::wstring ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(const wchar_t *& , std::wstring ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(const wchar_t *&& , std::wstring ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(const  wchar_t(&)[2], std::wstring ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(const  wchar_t(&&)[2], std::wstring ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(std::wstring_view , std::wstring ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(std::wstring_view & , std::wstring ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(std::wstring_view && , std::wstring ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(const std::wstring_view & , std::wstring ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(const std::wstring_view && , std::wstring ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(std::wstring , std::wstring ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(std::wstring & , std::wstring ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(std::wstring && , std::wstring ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(const std::wstring & , std::wstring ) |
| | **[CHECK_VALUE_OR](/libpalliate/generated/Namespaces/namespacetoml#function-check-value-or)**(const std::wstring && , std::wstring ) |
| | **[CHECK_INSERTED_AS](/libpalliate/generated/Namespaces/namespacetoml#function-check-inserted-as)**([table](/libpalliate/generated/Classes/classtable) , [table](/libpalliate/generated/Classes/classtable) ) |
| | **[CHECK_INSERTED_AS](/libpalliate/generated/Namespaces/namespacetoml#function-check-inserted-as)**([array](/libpalliate/generated/Classes/classarray) , [array](/libpalliate/generated/Classes/classarray) ) |
| | **[CHECK_INSERTED_AS](/libpalliate/generated/Namespaces/namespacetoml#function-check-inserted-as)**(node , node ) |
| | **[CHECK_INSERTED_AS](/libpalliate/generated/Namespaces/namespacetoml#function-check-inserted-as)**([time](/libpalliate/generated/Classes/structtime) , [value](/libpalliate/generated/Classes/classvalue)< [time](/libpalliate/generated/Classes/structtime) > ) |
| | **[CHECK_INSERTED_AS](/libpalliate/generated/Namespaces/namespacetoml#function-check-inserted-as)**(date , [value](/libpalliate/generated/Classes/classvalue)< date > ) |
| | **[CHECK_INSERTED_AS](/libpalliate/generated/Namespaces/namespacetoml#function-check-inserted-as)**([date_time](/libpalliate/generated/Classes/structdate__time) , [value](/libpalliate/generated/Classes/classvalue)< [date_time](/libpalliate/generated/Classes/structdate__time) > ) |
| | **[CHECK_INSERTED_AS](/libpalliate/generated/Namespaces/namespacetoml#function-check-inserted-as)**(bool , [value](/libpalliate/generated/Classes/classvalue)< bool > ) |
| | **[CHECK_INSERTED_AS](/libpalliate/generated/Namespaces/namespacetoml#function-check-inserted-as)**(int8_t , [value](/libpalliate/generated/Classes/classvalue)< int64_t > ) |
| | **[CHECK_INSERTED_AS](/libpalliate/generated/Namespaces/namespacetoml#function-check-inserted-as)**(int16_t , [value](/libpalliate/generated/Classes/classvalue)< int64_t > ) |
| | **[CHECK_INSERTED_AS](/libpalliate/generated/Namespaces/namespacetoml#function-check-inserted-as)**(int32_t , [value](/libpalliate/generated/Classes/classvalue)< int64_t > ) |
| | **[CHECK_INSERTED_AS](/libpalliate/generated/Namespaces/namespacetoml#function-check-inserted-as)**(int64_t , [value](/libpalliate/generated/Classes/classvalue)< int64_t > ) |
| | **[CHECK_INSERTED_AS](/libpalliate/generated/Namespaces/namespacetoml#function-check-inserted-as)**(uint8_t , [value](/libpalliate/generated/Classes/classvalue)< int64_t > ) |
| | **[CHECK_INSERTED_AS](/libpalliate/generated/Namespaces/namespacetoml#function-check-inserted-as)**(uint16_t , [value](/libpalliate/generated/Classes/classvalue)< int64_t > ) |
| | **[CHECK_INSERTED_AS](/libpalliate/generated/Namespaces/namespacetoml#function-check-inserted-as)**(uint32_t , [value](/libpalliate/generated/Classes/classvalue)< int64_t > ) |
| | **[CHECK_INSERTED_AS](/libpalliate/generated/Namespaces/namespacetoml#function-check-inserted-as)**(float , [value](/libpalliate/generated/Classes/classvalue)< double > ) |
| | **[CHECK_INSERTED_AS](/libpalliate/generated/Namespaces/namespacetoml#function-check-inserted-as)**(double , [value](/libpalliate/generated/Classes/classvalue)< double > ) |
| | **[CHECK_NODE_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-ref-type)**([table](/libpalliate/generated/Classes/classtable) ) |
| | **[CHECK_NODE_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-ref-type)**([array](/libpalliate/generated/Classes/classarray) ) |
| | **[CHECK_NODE_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-ref-type)**(std::string ) |
| | **[CHECK_NODE_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-ref-type)**(int64_t ) |
| | **[CHECK_NODE_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-ref-type)**(double ) |
| | **[CHECK_NODE_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-ref-type)**(bool ) |
| | **[CHECK_NODE_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-ref-type)**(date ) |
| | **[CHECK_NODE_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-ref-type)**([time](/libpalliate/generated/Classes/structtime) ) |
| | **[CHECK_NODE_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-ref-type)**([date_time](/libpalliate/generated/Classes/structdate__time) ) |
| | **[CHECK_NODE_VIEW_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-view-ref-type)**([table](/libpalliate/generated/Classes/classtable) ) |
| | **[CHECK_NODE_VIEW_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-view-ref-type)**([array](/libpalliate/generated/Classes/classarray) ) |
| | **[CHECK_NODE_VIEW_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-view-ref-type)**(std::string ) |
| | **[CHECK_NODE_VIEW_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-view-ref-type)**(int64_t ) |
| | **[CHECK_NODE_VIEW_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-view-ref-type)**(double ) |
| | **[CHECK_NODE_VIEW_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-view-ref-type)**(bool ) |
| | **[CHECK_NODE_VIEW_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-view-ref-type)**(date ) |
| | **[CHECK_NODE_VIEW_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-view-ref-type)**([time](/libpalliate/generated/Classes/structtime) ) |
| | **[CHECK_NODE_VIEW_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-node-view-ref-type)**([date_time](/libpalliate/generated/Classes/structdate__time) ) |
| | **[CHECK_CONST_NODE_VIEW_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-const-node-view-ref-type)**([table](/libpalliate/generated/Classes/classtable) ) |
| | **[CHECK_CONST_NODE_VIEW_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-const-node-view-ref-type)**([array](/libpalliate/generated/Classes/classarray) ) |
| | **[CHECK_CONST_NODE_VIEW_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-const-node-view-ref-type)**(std::string ) |
| | **[CHECK_CONST_NODE_VIEW_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-const-node-view-ref-type)**(int64_t ) |
| | **[CHECK_CONST_NODE_VIEW_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-const-node-view-ref-type)**(double ) |
| | **[CHECK_CONST_NODE_VIEW_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-const-node-view-ref-type)**(bool ) |
| | **[CHECK_CONST_NODE_VIEW_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-const-node-view-ref-type)**(date ) |
| | **[CHECK_CONST_NODE_VIEW_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-const-node-view-ref-type)**([time](/libpalliate/generated/Classes/structtime) ) |
| | **[CHECK_CONST_NODE_VIEW_REF_TYPE](/libpalliate/generated/Namespaces/namespacetoml#function-check-const-node-view-ref-type)**([date_time](/libpalliate/generated/Classes/structdate__time) ) |


## Functions Documentation

### function CHECK_NODE_TYPE_MAPPING

```cpp
CHECK_NODE_TYPE_MAPPING(
    int64_t ,
    node_type::integer 
)
```


### function CHECK_NODE_TYPE_MAPPING

```cpp
CHECK_NODE_TYPE_MAPPING(
    double ,
    node_type::floating_point 
)
```


### function CHECK_NODE_TYPE_MAPPING

```cpp
CHECK_NODE_TYPE_MAPPING(
    std::string ,
    node_type::string 
)
```


### function CHECK_NODE_TYPE_MAPPING

```cpp
CHECK_NODE_TYPE_MAPPING(
    bool ,
    node_type::boolean 
)
```


### function CHECK_NODE_TYPE_MAPPING

```cpp
CHECK_NODE_TYPE_MAPPING(
    toml::date ,
    node_type::date 
)
```


### function CHECK_NODE_TYPE_MAPPING

```cpp
CHECK_NODE_TYPE_MAPPING(
    toml::time ,
    node_type::time 
)
```


### function CHECK_NODE_TYPE_MAPPING

```cpp
CHECK_NODE_TYPE_MAPPING(
    toml::date_time ,
    node_type::date_time 
)
```


### function CHECK_NODE_TYPE_MAPPING

```cpp
CHECK_NODE_TYPE_MAPPING(
    toml::array ,
    node_type::array 
)
```


### function CHECK_NODE_TYPE_MAPPING

```cpp
CHECK_NODE_TYPE_MAPPING(
    toml::table ,
    node_type::table 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    time ,
    true 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    date ,
    true 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    date_time ,
    true 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    bool ,
    true 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    int8_t ,
    false 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    int16_t ,
    false 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    int32_t ,
    false 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    int64_t ,
    true 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    uint8_t ,
    false 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    uint16_t ,
    false 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    uint32_t ,
    false 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    uint64_t ,
    false 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    float ,
    false 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    double ,
    true 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    char * ,
    false 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    char [2],
    false 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    char(&) [2],
    false 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    const  char(&)[2],
    false 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    char(&&) [2],
    false 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    const  char(&&)[2],
    false 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    const char * ,
    true 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    std::string ,
    true 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    std::string_view ,
    true 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    wchar_t * ,
    false 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    wchar_t wchar_t[2],
    false 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    wchar_t(&) [2],
    false 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    const  wchar_t(&)[2],
    false 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    wchar_t(&&) [2],
    false 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    const  wchar_t(&&)[2],
    false 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    const wchar_t * ,
    false 
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    std::wstring ,
    !! TOML_ENABLE_WINDOWS_COMPAT
)
```


### function CHECK_CAN_REPRESENT_NATIVE

```cpp
CHECK_CAN_REPRESENT_NATIVE(
    std::wstring_view ,
    false 
)
```


### function CHECK_VALUE_EXACT

```cpp
CHECK_VALUE_EXACT(
    time ,
    time 
)
```


### function CHECK_VALUE_EXACT

```cpp
CHECK_VALUE_EXACT(
    date ,
    date 
)
```


### function CHECK_VALUE_EXACT

```cpp
CHECK_VALUE_EXACT(
    date_time ,
    date_time 
)
```


### function CHECK_VALUE_EXACT

```cpp
CHECK_VALUE_EXACT(
    bool ,
    bool 
)
```


### function CHECK_VALUE_EXACT

```cpp
CHECK_VALUE_EXACT(
    double ,
    double 
)
```


### function CHECK_VALUE_EXACT

```cpp
CHECK_VALUE_EXACT(
    int64_t ,
    int64_t 
)
```


### function CHECK_VALUE_EXACT

```cpp
CHECK_VALUE_EXACT(
    const char * ,
    const char * 
)
```


### function CHECK_VALUE_EXACT

```cpp
CHECK_VALUE_EXACT(
    std::string_view ,
    std::string_view 
)
```


### function CHECK_VALUE_EXACT

```cpp
CHECK_VALUE_EXACT(
    std::string ,
    std::string 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    time ,
    time 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    time & ,
    time 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    time && ,
    time 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    date ,
    date 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    date & ,
    date 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    date && ,
    date 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    date_time ,
    date_time 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    date_time & ,
    date_time 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    date_time && ,
    date_time 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    bool ,
    bool 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    bool & ,
    bool 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    bool && ,
    bool 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    int32_t ,
    int32_t 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    int32_t & ,
    int32_t 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    int32_t && ,
    int32_t 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    int64_t ,
    int64_t 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    int64_t & ,
    int64_t 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    int64_t && ,
    int64_t 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    float ,
    float 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    float & ,
    float 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    float && ,
    float 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    double ,
    double 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    double & ,
    double 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    double && ,
    double 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    char * ,
    const char * 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    char *& ,
    const char * 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    char *&& ,
    const char * 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    char [2],
    const char * 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    char(&) [2],
    const char * 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    char(&&) [2],
    const char * 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    const char * ,
    const char * 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    const char *& ,
    const char * 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    const char *&& ,
    const char * 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    const  char(&)[2],
    const char * 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    const  char(&&)[2],
    const char * 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    std::string_view ,
    std::string_view 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    std::string_view & ,
    std::string_view 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    std::string_view && ,
    std::string_view 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    const std::string_view & ,
    std::string_view 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    const std::string_view && ,
    std::string_view 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    std::string ,
    std::string 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    std::string & ,
    std::string 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    std::string && ,
    std::string 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    const std::string & ,
    std::string 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    const std::string && ,
    std::string 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    wchar_t * ,
    std::wstring 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    wchar_t *& ,
    std::wstring 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    wchar_t *&& ,
    std::wstring 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    wchar_t wchar_t[2],
    std::wstring 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    wchar_t(&) [2],
    std::wstring 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    wchar_t(&&) [2],
    std::wstring 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    const wchar_t * ,
    std::wstring 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    const wchar_t *& ,
    std::wstring 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    const wchar_t *&& ,
    std::wstring 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    const  wchar_t(&)[2],
    std::wstring 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    const  wchar_t(&&)[2],
    std::wstring 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    std::wstring_view ,
    std::wstring 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    std::wstring_view & ,
    std::wstring 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    std::wstring_view && ,
    std::wstring 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    const std::wstring_view & ,
    std::wstring 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    const std::wstring_view && ,
    std::wstring 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    std::wstring ,
    std::wstring 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    std::wstring & ,
    std::wstring 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    std::wstring && ,
    std::wstring 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    const std::wstring & ,
    std::wstring 
)
```


### function CHECK_VALUE_OR

```cpp
CHECK_VALUE_OR(
    const std::wstring && ,
    std::wstring 
)
```


### function CHECK_INSERTED_AS

```cpp
CHECK_INSERTED_AS(
    table ,
    table 
)
```


### function CHECK_INSERTED_AS

```cpp
CHECK_INSERTED_AS(
    array ,
    array 
)
```


### function CHECK_INSERTED_AS

```cpp
CHECK_INSERTED_AS(
    node ,
    node 
)
```


### function CHECK_INSERTED_AS

```cpp
CHECK_INSERTED_AS(
    time ,
    value< time > 
)
```


### function CHECK_INSERTED_AS

```cpp
CHECK_INSERTED_AS(
    date ,
    value< date > 
)
```


### function CHECK_INSERTED_AS

```cpp
CHECK_INSERTED_AS(
    date_time ,
    value< date_time > 
)
```


### function CHECK_INSERTED_AS

```cpp
CHECK_INSERTED_AS(
    bool ,
    value< bool > 
)
```


### function CHECK_INSERTED_AS

```cpp
CHECK_INSERTED_AS(
    int8_t ,
    value< int64_t > 
)
```


### function CHECK_INSERTED_AS

```cpp
CHECK_INSERTED_AS(
    int16_t ,
    value< int64_t > 
)
```


### function CHECK_INSERTED_AS

```cpp
CHECK_INSERTED_AS(
    int32_t ,
    value< int64_t > 
)
```


### function CHECK_INSERTED_AS

```cpp
CHECK_INSERTED_AS(
    int64_t ,
    value< int64_t > 
)
```


### function CHECK_INSERTED_AS

```cpp
CHECK_INSERTED_AS(
    uint8_t ,
    value< int64_t > 
)
```


### function CHECK_INSERTED_AS

```cpp
CHECK_INSERTED_AS(
    uint16_t ,
    value< int64_t > 
)
```


### function CHECK_INSERTED_AS

```cpp
CHECK_INSERTED_AS(
    uint32_t ,
    value< int64_t > 
)
```


### function CHECK_INSERTED_AS

```cpp
CHECK_INSERTED_AS(
    float ,
    value< double > 
)
```


### function CHECK_INSERTED_AS

```cpp
CHECK_INSERTED_AS(
    double ,
    value< double > 
)
```


### function CHECK_NODE_REF_TYPE

```cpp
CHECK_NODE_REF_TYPE(
    table 
)
```


### function CHECK_NODE_REF_TYPE

```cpp
CHECK_NODE_REF_TYPE(
    array 
)
```


### function CHECK_NODE_REF_TYPE

```cpp
CHECK_NODE_REF_TYPE(
    std::string 
)
```


### function CHECK_NODE_REF_TYPE

```cpp
CHECK_NODE_REF_TYPE(
    int64_t 
)
```


### function CHECK_NODE_REF_TYPE

```cpp
CHECK_NODE_REF_TYPE(
    double 
)
```


### function CHECK_NODE_REF_TYPE

```cpp
CHECK_NODE_REF_TYPE(
    bool 
)
```


### function CHECK_NODE_REF_TYPE

```cpp
CHECK_NODE_REF_TYPE(
    date 
)
```


### function CHECK_NODE_REF_TYPE

```cpp
CHECK_NODE_REF_TYPE(
    time 
)
```


### function CHECK_NODE_REF_TYPE

```cpp
CHECK_NODE_REF_TYPE(
    date_time 
)
```


### function CHECK_NODE_VIEW_REF_TYPE

```cpp
CHECK_NODE_VIEW_REF_TYPE(
    table 
)
```


### function CHECK_NODE_VIEW_REF_TYPE

```cpp
CHECK_NODE_VIEW_REF_TYPE(
    array 
)
```


### function CHECK_NODE_VIEW_REF_TYPE

```cpp
CHECK_NODE_VIEW_REF_TYPE(
    std::string 
)
```


### function CHECK_NODE_VIEW_REF_TYPE

```cpp
CHECK_NODE_VIEW_REF_TYPE(
    int64_t 
)
```


### function CHECK_NODE_VIEW_REF_TYPE

```cpp
CHECK_NODE_VIEW_REF_TYPE(
    double 
)
```


### function CHECK_NODE_VIEW_REF_TYPE

```cpp
CHECK_NODE_VIEW_REF_TYPE(
    bool 
)
```


### function CHECK_NODE_VIEW_REF_TYPE

```cpp
CHECK_NODE_VIEW_REF_TYPE(
    date 
)
```


### function CHECK_NODE_VIEW_REF_TYPE

```cpp
CHECK_NODE_VIEW_REF_TYPE(
    time 
)
```


### function CHECK_NODE_VIEW_REF_TYPE

```cpp
CHECK_NODE_VIEW_REF_TYPE(
    date_time 
)
```


### function CHECK_CONST_NODE_VIEW_REF_TYPE

```cpp
CHECK_CONST_NODE_VIEW_REF_TYPE(
    table 
)
```


### function CHECK_CONST_NODE_VIEW_REF_TYPE

```cpp
CHECK_CONST_NODE_VIEW_REF_TYPE(
    array 
)
```


### function CHECK_CONST_NODE_VIEW_REF_TYPE

```cpp
CHECK_CONST_NODE_VIEW_REF_TYPE(
    std::string 
)
```


### function CHECK_CONST_NODE_VIEW_REF_TYPE

```cpp
CHECK_CONST_NODE_VIEW_REF_TYPE(
    int64_t 
)
```


### function CHECK_CONST_NODE_VIEW_REF_TYPE

```cpp
CHECK_CONST_NODE_VIEW_REF_TYPE(
    double 
)
```


### function CHECK_CONST_NODE_VIEW_REF_TYPE

```cpp
CHECK_CONST_NODE_VIEW_REF_TYPE(
    bool 
)
```


### function CHECK_CONST_NODE_VIEW_REF_TYPE

```cpp
CHECK_CONST_NODE_VIEW_REF_TYPE(
    date 
)
```


### function CHECK_CONST_NODE_VIEW_REF_TYPE

```cpp
CHECK_CONST_NODE_VIEW_REF_TYPE(
    time 
)
```


### function CHECK_CONST_NODE_VIEW_REF_TYPE

```cpp
CHECK_CONST_NODE_VIEW_REF_TYPE(
    date_time 
)
```







_Automatically updated on 2022-05-02 at 01:42:11 +0000._
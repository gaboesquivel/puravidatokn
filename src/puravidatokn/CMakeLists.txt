cmake_minimum_required(VERSION 3.13)
project(puravidatokn)

set(EOSIO_WASM_OLD_BEHAVIOR "Off")
find_package(eosio.cdt)

add_contract( puravidatokn puravidatokn puravidatokn.cpp )

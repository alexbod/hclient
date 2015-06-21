# hclient
C++ Hbase client using the Thrift Server. See details at http://www.alexbod.com/c-plus-plus-hbase-client/.

# Compilation
g++ -Wall -o hclient main.cpp gen-cpp/Hbase_types.cpp gen-cpp/Hbase_constants.cpp gen-cpp/Hbase.cpp -lthrift

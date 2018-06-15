# FDM-3D-Printer-Slicing-Algorithm
FDM 3D 3-axes Printing Slicing algorithm with Matlab.
a program that can slices the stl (binary or ASCII) model into layers and autogenerate the GCode for 3-axes FDM 3D Printing. You can check the Gcode via Gcodeview&analyzer software and even Cura to illustrate the availability of autogenerated Gcodes.

* %direction%\stl_slicer_03_12_2018v2\Publish，this folder includes the publish documents of the MATLAB Program
* %direction%\stl_slicer_03_12_2018v2\Test_Models，this folder includes some STL models for testing the MATLAB program
* %dsirection%\stl_slicer_03_12_2018v2\Show_Result，this folder includes the Gcode autogenerated via the MATLAB program

Call the program via the main.m. The main.m call the other subfunctions (ex: slice_stl_create_path、triangle_plane_intersection、read_binary_stl_file、plot_slices_3D、plot_slices_2D、infill_outline、generate_gcode)

这是一个MATLAB程序，它可以将（二进制的或ASCII格式的）STL模型切片并自动生成用于熔融沉积3轴3D打印机的G代码。你可以通过Gcodeview&analyzer甚至Cura软件检查生成的G代码的以验证G代码的有效性。

%direction%\stl_slicer_03_12_2018v2\Publish，此文件下是该程序的发布文档
%direction%\stl_slicer_03_12_2018v2\Test_Models，此文件夹下是一些用于测试程序的模型
%direction%\stl_slicer_03_12_2018v2\Show_Result，此文件夹下是自动生成的模型的G代码

请调用主程序main.m. 这个main.m 调用了所有子函数（比如：slice_stl_create_path、triangle_plane_intersection、read_binary_stl_file、plot_slices_3D、plot_slices_2D、infill_outline、generate_gcode）

.. _eu.gmic.Frameblur:

G’MIC Frame blur node
=====================

*This documentation is for version 0.3 of G’MIC Frame blur.*

Description
-----------

Author: David Tschumperle. Latest update: 2014/19/01.

Wrapper for the G’MIC framework (http://gmic.eu) written by Tobias Fleischer (http://www.reduxfx.com).

Inputs
------

+-------+-------------+----------+
| Input | Description | Optional |
+=======+=============+==========+
| Input |             | No       |
+-------+-------------+----------+

Controls
--------

.. tabularcolumns:: |>{\raggedright}p{0.2\columnwidth}|>{\raggedright}p{0.06\columnwidth}|>{\raggedright}p{0.07\columnwidth}|p{0.63\columnwidth}|

.. cssclass:: longtable

+-----------------------------------------------+---------+-------------------------------------+-----------------------+
| Parameter / script name                       | Type    | Default                             | Function              |
+===============================================+=========+=====================================+=======================+
| Horizontal size (%) / ``Horizontal_size_``    | Double  | 30                                  |                       |
+-----------------------------------------------+---------+-------------------------------------+-----------------------+
| Vertical size (%) / ``Vertical_size_``        | Double  | 30                                  |                       |
+-----------------------------------------------+---------+-------------------------------------+-----------------------+
| Crop / ``Crop``                               | Double  | 0                                   |                       |
+-----------------------------------------------+---------+-------------------------------------+-----------------------+
| Blur / ``Blur``                               | Double  | 5                                   |                       |
+-----------------------------------------------+---------+-------------------------------------+-----------------------+
| Roundness / ``Roundness``                     | Double  | 0                                   |                       |
+-----------------------------------------------+---------+-------------------------------------+-----------------------+
| Apply color balance / ``Apply_color_balance`` | Boolean | Off                                 |                       |
+-----------------------------------------------+---------+-------------------------------------+-----------------------+
| Balance color / ``Balance_color``             | Color   | r: 0.501961 g: 0.501961 b: 0.501961 |                       |
+-----------------------------------------------+---------+-------------------------------------+-----------------------+
| Normalization / ``Normalization``             | Choice  | None                                | |                     |
|                                               |         |                                     | | **None**            |
|                                               |         |                                     | | **Stretch**         |
|                                               |         |                                     | | **Equalize**        |
+-----------------------------------------------+---------+-------------------------------------+-----------------------+
| Outline size / ``Outline_size``               | Double  | 5                                   |                       |
+-----------------------------------------------+---------+-------------------------------------+-----------------------+
| Outline color / ``Outline_color``             | Color   | r: 1 g: 1 b: 1                      |                       |
+-----------------------------------------------+---------+-------------------------------------+-----------------------+
| X-shadow / ``Xshadow``                        | Double  | 2                                   |                       |
+-----------------------------------------------+---------+-------------------------------------+-----------------------+
| Y-shadow / ``Yshadow``                        | Double  | 2                                   |                       |
+-----------------------------------------------+---------+-------------------------------------+-----------------------+
| Shadow smoothness / ``Shadow_smoothness``     | Double  | 1                                   |                       |
+-----------------------------------------------+---------+-------------------------------------+-----------------------+
| Shadow contrast / ``Shadow_contrast``         | Double  | 0                                   |                       |
+-----------------------------------------------+---------+-------------------------------------+-----------------------+
| X-centering / ``Xcentering``                  | Double  | 0.5                                 |                       |
+-----------------------------------------------+---------+-------------------------------------+-----------------------+
| Y-centering / ``Ycentering``                  | Double  | 0.5                                 |                       |
+-----------------------------------------------+---------+-------------------------------------+-----------------------+
| Angle / ``Angle``                             | Double  | 0                                   |                       |
+-----------------------------------------------+---------+-------------------------------------+-----------------------+
| Output Layer / ``Output_Layer``               | Choice  | Layer 0                             | |                     |
|                                               |         |                                     | | **Merged**          |
|                                               |         |                                     | | **Layer 0**         |
|                                               |         |                                     | | **Layer 1**         |
|                                               |         |                                     | | **Layer 2**         |
|                                               |         |                                     | | **Layer 3**         |
|                                               |         |                                     | | **Layer 4**         |
|                                               |         |                                     | | **Layer 5**         |
|                                               |         |                                     | | **Layer 6**         |
|                                               |         |                                     | | **Layer 7**         |
|                                               |         |                                     | | **Layer 8**         |
|                                               |         |                                     | | **Layer 9**         |
+-----------------------------------------------+---------+-------------------------------------+-----------------------+
| Resize Mode / ``Resize_Mode``                 | Choice  | Dynamic                             | |                     |
|                                               |         |                                     | | **Fixed (Inplace)** |
|                                               |         |                                     | | **Dynamic**         |
|                                               |         |                                     | | **Downsample 1/2**  |
|                                               |         |                                     | | **Downsample 1/4**  |
|                                               |         |                                     | | **Downsample 1/8**  |
|                                               |         |                                     | | **Downsample 1/16** |
+-----------------------------------------------+---------+-------------------------------------+-----------------------+
| Ignore Alpha / ``Ignore_Alpha``               | Boolean | Off                                 |                       |
+-----------------------------------------------+---------+-------------------------------------+-----------------------+
| Log Verbosity / ``Log_Verbosity``             | Choice  | Off                                 | |                     |
|                                               |         |                                     | | **Off**             |
|                                               |         |                                     | | **Level 1**         |
|                                               |         |                                     | | **Level 2**         |
|                                               |         |                                     | | **Level 3**         |
+-----------------------------------------------+---------+-------------------------------------+-----------------------+

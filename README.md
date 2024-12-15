# omics-tools-table
This repository contains a table that summarizes some of the available tools for analyzing omics data. 

<!DOCTYPE html>
<html>
<head>
  <title>Genomics Tools Table</title>
  <!-- DataTables CSS -->
  <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.13.1/css/jquery.dataTables.css">
</head>
<body>
  <h1>Interactive Genomics Tools Table</h1>
  <p>Below is a searchable and sortable table of genomics tools:</p>

  <table id="toolsTable" class="display">
    <thead>
      <tr>
        <th>Tool</th>
        <th>Category</th>
        <th>Description</th>
        <th>Link</th>
        <th>Comments</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>FastQC</td>
        <td>Analysis</td>
        <td>Quality control for sequencing data</td>
        <td><a href="https://www.bioinformatics.babraham.ac.uk/projects/fastqc/" target="_blank">Visit</a></td>
        <td>Great for identifying issues in raw reads</td>
      </tr>
      <tr>
        <td>Bowtie</td>
        <td>Sequencing</td>
        <td>Fast and memory-efficient aligner</td>
        <td><a href="http://bowtie-bio.sourceforge.net/index.shtml" target="_blank">Visit</a></td>
        <td>Often used in RNA-seq pipelines</td>
      </tr>
      <tr>
        <td>IGV</td>
        <td>Visualization</td>
        <td>Interactive genome viewer</td>
        <td><a href="https://software.broadinstitute.org/software/igv/" target="_blank">Visit</a></td>
        <td>Supports various genome formats</td>
      </tr>
      <tr>
        <td>Trimmomatic</td>
        <td>Analysis</td>
        <td>Trimming and filtering of reads</td>
        <td><a href="http://www.usadellab.org/cms/?page=trimmomatic" target="_blank">Visit</a></td>
        <td>Handles both single-end and paired-end data</td>
      </tr>
    </tbody>
  </table>

  <!-- jQuery -->
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
  <!-- DataTables JS -->
  <script src="https://cdn.datatables.net/1.13.1/js/jquery.dataTables.js"></script>
  <script>
    $(document).ready(function() {
      $('#toolsTable').DataTable();
    });
  </script>
</body>
</html>

### Adding new tools
To add new tools to the existing table, replace the <tr> blocks inside <tbody> with rows for the new tools. Each row represents one tool.

_Example_
<tr>
  <td>Tool Name</td>
  <td>Category</td>
  <td>Short Description</td>
  <td><a href="URL" target="_blank">Visit</a></td>
  <td>Comments</td>
</tr>
